PROYECTO INDIVIDUAL N°1-Cohorte 08

Autor: Renzo Sosa
Usuario de Github: Renzo96

Machine Learning Operations(MLOps)

Este proyecto consiste en la transformación de datos de un dataset de plataformas de streaming populares como Netflix, Hulu, Amazon y Disney+.Utilizando las herramientas de procesamiento de datos de Python, se realizan limpieza, filtrado y agregación de los datos con el fin de prepararlos para su análisis posterior. Esto fue realizado a través de un ETL, archivo que encontrará en la carpeta código.


A continuación, se utiliza FastAPI para construir un conjunto de cuatro consultas a la base de datos de streaming. Estas consultas están diseñadas para obtener información relevante sobre el comportamiento de los usuarios, la popularidad de los contenidos y las tendencias de visualización en las plataformas de streaming. La api esta compuesta por cuatro consultas: 

-pelicula de mayor duración

-Cantidad de películas por plataforma con un puntaje mayor a XX en determinado año

-Cantidad de películas por plataforma con filtro de PLATAFORMA

-Actor que más se repite según plataforma y año


Después de implementar el proyecto, se procede a realizar un análisis exploratorio de datos (EDA) para obtener información más detallada sobre los datos y su distribución. Con el EDA completado, se construye un sistema de recomendación utilizando el score de los usuarios en el dataset de streaming.

Habiendo concluido el EDA, se pasa al modelo de recomendación, el cual es alimentado por el csv obtenido en el EDA.

En resumen, este proyecto utiliza herramientas de procesamiento de datos, FastAPI,para construir una aplicación web que proporciona información sobre las tendencias de visualización y comportamiento de los usuarios en las plataformas de streaming. Además, se construye un sistema de recomendación basado en los datos para ayudar a los usuarios a descubrir nuevos contenidos de streaming que les puedan interesar, en base a las anteriores películas que han observado.
