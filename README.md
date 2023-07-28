# Wines

In this notebook, we work from two datasets in which two lists of wines and their corresponding characteristics are collected, such as the levels of chlorides, sulphates or residual sugar, among others.

Initially, there is a dataset for white wines and another for red wines, but for data processing we join them into one, creating a new column that classifies them precisely by whites/reds.

Once we have the complete dataframe, we carry out the exercise of trying to predict whether a wine will be white or red based on its characteristics, obtaining good metrics with the classifier. We also try to predict the quality of the wine, but in this case the metrics do not reach a minimally desirable level, we understand that because quality can be a parameter with a certain level of subjectivity and not so dependent on its chemical characteristics.

##########################

ES
En este notebook trabajamos a partir de dos datasets en los que se recogen sendos listados de vinos y sus correspondientes características, como por ejemplo los niveles de cloruros, sulfatos o el azúcar residual, entre otros.

Inicialmente hay un dataset para los vinos blancos y otro para los tintos, pero para el tratamiento de datos los unimos en uno solo, creando una nueva columna que los clasifica precisamente por blancos/tintos.

Una vez tenemos el dataframe completo, realizamos el ejercicio de tratar de predecir si un vino será blanco o tinto en base a sus características, obteniendo unas buenas métricas con el clasificador. Se intenta también predecir la calidad del vino, pero en este caso las métricas no alcanzan un nivel mínimamente deseable, entendemos que porque la calidad puede ser un parámetro con cierto nivel de subjetividad y no tan dependiente de sus características químicas.
