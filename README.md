# Nuclio_DS_Projects
Data Science Projects developed during Nuclio Bootcamp

### 1. **[Malware predicition](Malware_prediction)**: 
El objetivo de este ejercicio es estimar la probabilidad de que una máquina con Sistema Operativo Windows se vea infectada por algún tipo de malware, en base a las distintas propiedades de la máquina. Los datos para este ejercicio se encuentran en la siguiente url: https://www.dropbox.com/s/sxl5bpi2620p496/sample_mmp.csv

Y se han obtenido muestreando el dataset original de la competición de Kaggle Microsoft Malware Prediction (https://www.kaggle.com/c/microsoft-malwareprediction), y se basan en las características obtenidas en la solución de endpoint Windows Defender. Cada fila del dataset corresponde a una máquina única, identificada por el campo MachineIdentifier. El target es la variable HasDetections, que indica que se ha detectado Malware en la máquina.

- Se realiza una exploración exhaustiva de los datos, el preprocesamiento, el modelado mediante un Decision Tree, un Random Forest, Gradient boosting y xgboost y se comparan las métricas obtenidas con cada uno, más una evaluación final.

### 2. **[K-means con transformers/pipelines de sklearn]**
En este notebook vamos a trabajar con el dataset de la compañia brasileña de E-Commerce llamada Olist.

Utilizando el dataset de Olist (alrededor de 100 mil registros) vamos a construir una segmentacion basada en el algoritmo KMeans. El enfoque a la hora de construir variables será basado en el modelo de RFM (recency - frequency - monetary value). Esta es una forma de trabajar muy común en startups y tiendas online donde se dispone de poca información de los clientes y la retención/canje de los clicks es fundamental.
