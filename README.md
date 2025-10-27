# Explorador de Países - Proyecto Flutter

Este es un proyecto de aprendizaje para un curso de Flutter, diseñado para aplicar y consolidar conocimientos en el desarrollo de aplicaciones móviles.

## 1. ¿Qué hará la aplicación?

**"Explorador de Países"** será una aplicación móvil que permitirá a los usuarios explorar información sobre todos los países del mundo. La aplicación obtendrá los datos de una API pública (`restcountries.com`) y los presentará en una interfaz limpia e intuitiva.

Las funciones principales incluyen:
- Mostrar una lista completa de países.
- Permitir la búsqueda y filtrado de países en tiempo real.
- Ver detalles específicos de un país seleccionado (capital, población, bandera, etc.).
- Posibles: ¿Mostrar la diferencia horaria?, ver la Wikipedia del país

## 2. ¿A quién va dirigida?

El público objetivo principal es **gente que necesita saber algo sobre los países del mundo por los que viaja**. El proyecto está diseñado para ser un ejercicio práctico que integra:

- Consumo de APIs REST.
- Modelado de datos (JSON a objetos Dart).
- Navegación entre pantallas.
- Manejo de estado (carga, éxito, error).
- Creación de una interfaz de usuario dinámica y atractiva.

Para el usuario final, es una herramienta de consulta rápida y educativa.

## 3. Pantallas y Funciones

### Pantalla 1: Lista de Países (Pantalla Principal)
- **Función:** Muestra una lista de todos los países.
- **Componentes:**
  - Una barra de búsqueda para filtrar la lista.
  - Un `ListView` que muestra la bandera y el nombre de cada país.
  - Un indicador de carga (`CircularProgressIndicator`) mientras se obtienen los datos.
  - Navegación a la pantalla de detalles al tocar un país.

### Pantalla 2: Detalles del País
- **Función:** Muestra información detallada de un país seleccionado.
- **Componentes:**
  - La bandera del país en grande.
  - Datos clave como: Capital, Población, Continente, etc.
  - Diferencia horaria
  - Wikipedia del país

