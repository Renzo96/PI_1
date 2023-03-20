PROYECTO INDIVIDUAL N°1 

Machine Learning Operations(MLOps)

Este proyecto consiste en la transformación de datos de un dataset de plataformas de streaming populares como Netflix, Hulu, Amazon y Disney+.Utilizando las herramientas de procesamiento de datos de Python, se realizan limpieza, filtrado y agregación de los datos con el fin de prepararlos para su análisis posterior.

A continuación, se utiliza FastAPI para construir un conjunto de cuatro consultas a la base de datos de streaming. Estas consultas están diseñadas para obtener información relevante sobre el comportamiento de los usuarios, la popularidad de los contenidos y las tendencias de visualización en las plataformas de streaming.


Después de implementar el proyecto, se procede a realizar un análisis exploratorio de datos (EDA) para obtener información más detallada sobre los datos y su distribución. Con el EDA completado, se construye un sistema de recomendación utilizando el score de los usuarios en el dataset de streaming.

En resumen, este proyecto utiliza herramientas de procesamiento de datos, FastAPI,para construir una aplicación web que proporciona información sobre las tendencias de visualización y comportamiento de los usuarios en las plataformas de streaming. Además, se construye un sistema de recomendación basado en los datos para ayudar a los usuarios a descubrir nuevos contenidos de streaming que les puedan interesar.

PASOS REALIZADOS EN EL PROYECTO:

Lo primero que realize (archivo 1-Primerastransformaciones.py) fueron las transformaciones de datos detalladas y documentadas en el archivo .py.

Luego de generar las transformaciones procedi a generar 4 consultas con fastApi a traves de funciones de Python, las consultas fueron:

->get_max_duration: Película con mayor duración con filtros opcionales de AÑO, PLATAFORMA Y TIPO DE DURACIÓN.

->get_score_count: Cantidad de películas por plataforma con un puntaje mayor a XX en determinado año.

->get_count_platform: Cantidad de películas por plataforma con filtro de PLATAFORMA.

->get_actor: Actor que más se repite según plataforma y año.

Una vez creadas las consultas en fastApi, cree una app en Space para poder deployarla y que este disponible publicamente. Mi aplicacion se llama "apiiii" y se puede acceder a traves del siguente link: