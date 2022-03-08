# Nuclio_DS_Projects
Data Science Projects developed during Nuclio Bootcamp

##1. **Malware_predicition**: 
El objetivo de este ejercicio es estimar la probabilidad de que una máquina con Sistema Operativo Windows se vea infectada por
algún tipo de malware, en base a las distintas propiedades de la máquina. Los datos para este ejercicio se encuentran en la
siguiente url:

https://www.dropbox.com/s/sxl5bpi2620p496/sample_mmp.csv

Y se han obtenido muestreando el dataset original de la competición de Kaggle Microsoft Malware Prediction
(https://www.kaggle.com/c/microsoft-malwareprediction), y se basan en las características obtenidas en la solución de endpoint
Windows Defender. Cada fila del dataset corresponde a una máquina única, identificada por el campo MachineIdentifier. El target es
la variable HasDetections, que indica que se ha detectado Malware en la máquina.
