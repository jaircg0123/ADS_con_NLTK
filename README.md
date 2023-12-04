# PLN_PROYECTO_LuisJairCruzGarcia
Analisis de Sentimientos usando la librería NLTK de python

Este proyecto se divide en 3 etapas

Etapa 1: Analisis exploratorio de los datos 


En esta etapa se importan las librerias necesarias para realizar el proyecto, se carga importa el dataset usando pandas y se exploran las columnas del dataframe paratener una imagen completa de los datos con los que se estan trabajando

Etapa 2: Analsis de sentimientos

En esta etapa se hace uso de la librería NLTK de python para hacer el analisis de sentimientos de las reseñas de personas respecto a la adaptación a live-action del anime “One Piece”.  Para hacer esto primero se hace un pre-procesamiento del texto para despues usar un Analizador de sentimientos para determinar si la reseña fue positva o negativa. 

Etapa 3: Creación de un modelo de ML

Finalmente se construye un modelo de machine learning para predecir la calificación que las personas le otorgaron a la serie en base a su reseña. Para este modelo se toma como caracteristicas el analisis de sentiientos de la etapa anterior.
