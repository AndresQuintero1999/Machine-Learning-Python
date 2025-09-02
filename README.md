# Machine-Learning-Python
Proyecto creado para comparar técnicas de preprocesamiento en modelos predictivos de Machine Learning para clasificar enfermedades cardiacas y analizar la relevancia de las variables fisiológicas mediante visualización con SHAP.

En el proyecto se implementó 2 conjutno de datos, el 1er conjutno de datos (Cardiovascular_Disease_Dataset.csv) se usó para pruebas y testeo, el 2do conjunto de datos (Cardiovascular_Disease_Dataset_2.csv) se usó para validar cada técnica o paso que se hacia.

El archivo Cardiovascular_filter_EDA.ipynb contiene el análisis exploratorio de los datos para el 1er conjunto de datos. Distribucciones de datos, correlaciones y boxplots.
El archivo Cardiovscular_filter_dataset_2.ipynb contiene un pequeño análsisi exploratorio de los datos del 2do conjunto de datos y adicionalmente un filtrado del mismo (encoding, imputación de observaciones).
El archivo Cardiovascular_filter_PCA_2.ipynb contiene la comparación de ambos conjuntos de datos aplicandoles primero una PCA unica y luego normalización, PCA y SMOTE. La PCA aplicada es de 2 componentes.
El archivo Cardiovascular_filter_PCA_3.ipynb similar que el anterior, solo que la PCA es de 3 componentes.
El archivo Cardiovascular_filter.ipynb contiene la comparación paso a paso de ambos conjuntos de datos sin uso de PCA, tenemos la comparación de datos crudos, comparación de los datos normalizados y balanceados, y comparación de tuneo de hiperparámetros. En este aplicamos la visualización por SHAP para ver la importancia de cada caracteristica.
Por último, el archivo Auxiliar_functions.ipynb contiene funciones auxiliares que se ejecutan en los scripts anteriores


