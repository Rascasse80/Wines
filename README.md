# Wines

En este notebook trabajamos a partir de dos datasets en los que se recogen sendos listados de vinos y sus correspondientes características, como por ejemplo los niveles de cloruros, sulfatos o el azúcar residual, entre otros.

Inicialmente hay un dataset para los vinos blancos y otro para los tintos, pero para el tratamiento de datos los unimos en uno solo, creando una nueva columna que los clasifica precisamente por blancos/tintos.

Una vez tenemos el dataframe completo, realizamos el ejercicio de tratar de predecir si un vino será blanco o tinto en base a sus características, obteniendo unas buenas métricas con el clasificador. Se intenta también predecir la calidad del vino, pero en este caso las métricas no alcanzan un nivel mínimamente deseable, entendemos que porque la calidad puede ser un parámetro con cierto nivel de subjetividad y no tan dependiente de sus características químicas.
