# Actividad 5: Manejo de Datos con Pandas

## Descripción del Proyecto

Este proyecto es una actividad académica del séptimo trimestre de la carrera de Data Science, enfocada en el manejo y análisis de datos utilizando la biblioteca Pandas de Python. El objetivo principal es demostrar habilidades prácticas en la manipulación de datos a través de una serie de ejercicios que cubren desde la creación de Series y DataFrames hasta operaciones avanzadas como filtrado, manejo de valores faltantes y lectura/escritura de archivos CSV.

El proyecto incluye un notebook de Jupyter (`analisis.ipynb`) que contiene ejercicios paso a paso sobre los siguientes temas:

- Creación y operaciones con Series.
- Creación y exploración de DataFrames.
- Inspección y exploración de datos.
- Acceso a columnas y filas.
- Operaciones básicas de transformación.
- Filtrado de datos.
- Manejo de valores faltantes (nulos).
- Lectura y guardado de datos en formato CSV.
- Un ejercicio integrado que combina múltiples operaciones.

Los datos utilizados son un dataset ficticio de personas con información como nombre, edad, ciudad e ingreso, lo que permite practicar técnicas reales de análisis de datos.

## Instalación

Para ejecutar este proyecto, necesitas tener Python instalado en tu sistema. Se recomienda usar un entorno virtual para evitar conflictos con otras dependencias.

### Requisitos Previos

- Python 3.8 o superior.
- Jupyter Notebook o JupyterLab para ejecutar el notebook.

### Pasos de Instalación

1. Clona o descarga este repositorio en tu máquina local.
2. Navega al directorio del proyecto:
   ```
   cd c:/Users/ultra/Universidad/Septimo trimestre/Data science/fdoc_cd_act5
   ```
3. Instala las dependencias utilizando el archivo `requirements.txt`:

   ```
   pip install -r requirements.txt
   ```

   Esto instalará todas las bibliotecas necesarias, incluyendo Pandas, NumPy, Jupyter y otras dependencias para el entorno de desarrollo.

4. Una vez instaladas las dependencias, puedes abrir el notebook con:
   ```
   jupyter notebook analisis.ipynb
   ```
   O si usas JupyterLab:
   ```
   jupyter lab analisis.ipynb
   ```

## Uso

1. Abre el notebook `analisis.ipynb` en Jupyter Notebook o JupyterLab.
2. Ejecuta las celdas en orden secuencial para ver los resultados de cada ejercicio.
3. Los ejercicios están numerados del 1 al 9, cada uno enfocándose en un aspecto específico de Pandas.
4. Al final del notebook, se generan archivos CSV como `actividad_semana5.csv`, `personas_seleccion.csv` y `personas_filtradas.csv` que puedes revisar.

El notebook está diseñado para ser educativo, con explicaciones en cada sección y ejemplos prácticos. Puedes modificar los datos o agregar más ejercicios según tus necesidades.

## Contenido del Proyecto

- `analisis.ipynb`: Notebook principal con todos los ejercicios de Pandas.
- `info.json`: Información del autor del proyecto.
- `requirements.txt`: Lista de dependencias de Python necesarias.
- `README.md`: Este archivo de documentación.
- Archivos generados durante la ejecución:
  - `actividad_semana5.csv`: Dataset base exportado.
  - `personas_seleccion.csv`: CSV con columnas seleccionadas.
  - `personas_filtradas.csv`: Resultado del ejercicio integrado.

## Autor

- **Nombre**: Andrés Sebastián Ospina Guzmán
- **Grupo**: 3145939
- **Institución**: Universidad (Séptimo trimestre, Data Science)

## Licencia

Este proyecto es para fines académicos y no tiene una licencia específica asignada. Siéntete libre de usarlo como referencia para tus propios estudios.
