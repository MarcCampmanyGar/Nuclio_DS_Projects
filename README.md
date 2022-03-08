# Nuclio_DS_Projects
Data Science Projects developed during Nuclio Bootcamp

### 1. **[Malware prediction](Malware_Prediction.ipynb)**: 
El objetivo de este ejercicio es estimar la probabilidad de que una máquina con Sistema Operativo Windows se vea infectada por algún tipo de malware, en base a las distintas propiedades de la máquina. Los datos se han obtenido muestreando el dataset original de la competición de Kaggle Microsoft Malware Prediction (https://www.kaggle.com/c/microsoft-malwareprediction), y se basan en las características obtenidas en la solución de endpoint Windows Defender. Cada fila del dataset corresponde a una máquina única, identificada por el campo MachineIdentifier. El target es la variable HasDetections, que indica que se ha detectado Malware en la máquina.

- Se realiza una exploración exhaustiva de los datos, el preprocesamiento, el modelado mediante un Decision Tree, un Random Forest, Gradient boosting y xgboost y se comparan las métricas obtenidas con cada uno, más una evaluación final.

### 2. **[K-means con transformers/pipelines de sklearn](03_KMeans_with_pipelines.ipynb)**
En este notebook se trabaja con el dataset de la compañia brasileña de E-Commerce llamada Olist.

Utilizando el dataset de Olist (alrededor de 100 mil registros) se construye una segmentacion basada en el algoritmo KMeans. El enfoque a la hora de construir variables será basado en el modelo de RFM (recency - frequency - monetary value). Se crean también transformers y pipelines para automatizar el procesamiento de la información.

### 3. **[Series Temporales](Series_Temporales.ipynb)**
Análisis y estudio de ARIMA para la predicción temporal de un dataset básico creado por nosotros.

### 4. **[PCA y collaborative Filtering](PCA_CF_Anime.ipynb)**
Crearemos 2 modelos CF: uno basando en usuarios (personas similares a ti, han comprado/visto/les ha gustado estas cosas) y otro basado en productos (las personas que han comprado este producto, también han comprado estos).El dataset que vamos a utilizar es un dataset de Animes japoneses.
Nuestros principales objetivos serán:
- Hace una exploración inicial de los dos datasets y entender la distribución de los datos.
- Extraer algunas variables útiles como podrían ser: género de los animes y eliminar usuarios que no han puntuado los animes.
- Reducir la dimensionalidad de nuestro DataFrame utilizando el PCA
- Segmentar nuestros clientes utilizando el dataset reducido
- Utilizar la similitud del coseno para hacer recomendaciones a nuestro clientes (user and product based)

### 5. **[Deep Learning]**
Trabajar con el dataset de imágenes CIFAR-10 para optimizar un modelo y conseguir superar el 90% de accuracy en la predicción de clases.
