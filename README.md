# netflix-dataset-analysis
Análisis y visualización de datos del catálogo de Netflix, incluyendo limpieza y transformación de datos

## Descripción
Este proyecto se centra en el análisis y la visualización de datos del catálogo de Netflix. Incluye pasos de limpieza y transformación de datos, así como análisis descriptivo y visualizaciones para explorar diversos aspectos del contenido de Netflix.

## Contenido
- `netflix1.csv`: Dataset original utilizado para el análisis.
- `netflix_analyzed.csv`: Dataset limpio y transformado con análisis adicionales.
- `notebook.ipynb`: Jupyter Notebook con el código para la limpieza, transformación y análisis de datos.
- `README.md`: Este archivo con la descripción del proyecto.

## Análisis Realizados
1. **Limpieza de Datos**:
    - Eliminación de columnas innecesarias.
    - Manejo de valores nulos y faltantes.
    - Conversión de tipos de datos.

2. **Transformación de Datos**:
    - Creación de la columna `primary_genre` a partir de `listed_in`.

3. **Visualizaciones y Exploración de Datos**:
    - Distribución de tipos de contenido.
    - Análisis por país de producción.
    - Distribución de años de lanzamiento.
    - Análisis de géneros principales.
    - Distribución de la duración del contenido.

## Herramientas Utilizadas
- Python
- Pandas
- Matplotlib
- Seaborn

## Instrucciones para Reproducir el Proyecto
1. Clonar el repositorio:
    ```sh
    git clone https://github.com/lucas2356/netflix-data-analysis.git
    cd netflix-data-analysis
    ```

2. Instalar las dependencias necesarias:
    ```sh
    pip install pandas matplotlib seaborn
    ```

3. Ejecutar el Jupyter Notebook:
    ```sh
    jupyter notebook notebook.ipynb
    ```

## Contribuciones
Las contribuciones son bienvenidas. Por favor, crea un pull request o abre un issue para discutir cualquier cambio que desees realizar.

## Licencia
Este proyecto está bajo la Licencia MIT.

