# Topicos de Telemática - Proyecto de Big Data

Video-sustentación: https://youtu.be/1GedQ4K5oPo

Por: Diego Andrés Giraldo Gómez

Estos fueron los pasos que seguí para realizar el proyecto:

1. Entender el problema de las noticias para empezar a trabajar en él
2. Entender la solución requerida para dicho problema
3. Buscar dataset adecuado para la solución, usé articlespart1.csv de https://www.kaggle.com/snapcrack/all-the-news/version/1 
4. Crear cluster y notebook en Amazon
5. Subir el dataset a S3 para poder trabajar con él en el notebook
6. Realizar la parte de preparación de datos de la práctica que incluye:
  - Remover caracteres especiales (. , % ( ) ‘ “ ….
  - Remover stop-words
  - Remover palabras de longitud 1
  - Stemming / lemmatization
