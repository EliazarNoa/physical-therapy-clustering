# Clustering de Ejercicios de Terapia Física con Sensores de Movimiento Vestibles

Este proyecto utiliza algoritmos de clustering para analizar datos recopilados mediante sensores de movimiento vestibles durante sesiones de terapia física. Los sensores registran ejecuciones de ejercicios realizados por pacientes. Implementamos el algoritmo MTMM-DTW para detectar y evaluar secuencias de ejercicios, proporcionando una clasificación objetiva de la ejecución y contabilizando el número de repeticiones. El sistema autónomo permite un monitoreo preciso y automatizado, brindando información valiosa tanto a los pacientes como a los especialistas en terapia física. El repositorio en GitHub contiene notebooks que cubren desde el análisis exploratorio hasta la evaluación del modelo, junto con archivos fuente y resultados. 

---



## Estructura del Proyecto

- `data/`: Contiene el conjunto de datos y cualquier archivo relacionado.
- `notebooks/`: Notebooks de Jupyter que abarcan el análisis exploratorio, la ingeniería de características y el modelado.
- `src/`: Código fuente, incluyendo implementaciones de algoritmos como MTMM-DTW y funciones de clustering.
- `results/`: Resultados del proyecto, como archivos CSV y visualizaciones.
- `results/images/`: Imágenes generadas por el proyecto.

## Notebooks

1. [Exploratory Data Analysis](notebooks/01_Exploratory_Data_Analysis.ipynb)
2. [Feature Engineering](notebooks/02_Feature_Engineering.ipynb)
3. [Data Preparation](notebooks/03_Data_Preparation.ipynb)
4. [Modeling](notebooks/04_Modeling.ipynb)
5. [Model Evaluation](notebooks/05_Model_Evaluation.ipynb)

## Código Fuente

- `src/mtmm_dtw.py`: Implementación del algoritmo MTMM-DTW.
- `src/clustering.py`: Funciones para realizar el clustering de los datos.

## Resultados

- `results/clustering_results.csv`: Archivo CSV con los resultados del clustering.

## Contribuir

Si quieres contribuir a este proyecto, ¡no dudes en abrir un issue o enviar un pull request!

## Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).
