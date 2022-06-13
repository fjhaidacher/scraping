
#Tarea #1 Grupo: Franz Heidacher, Jaime Garcia y Victor de Leon
#Curso Text Minning
#Pedro 

#Se creó environment scrapping-tripadvisor en Anaconda llamado scrapping-tripadvisor
#Se instaló scrapy con pip install scrapy
#Se aperturó terminal para envío de comandos scrapy (scrapy shell, scrapy startproject, scrapy genspider, scrapy crawl)

#Se editó en editor de texto (notepad) los archivos .py para configuración y edición de spider.py

#Comandos específicos utilizados
C:\Users\vdeleon\Anaconda3\envs\tripadvisor2>scrapy shell "https://www.tripadvisor.com/Hotels-g153373-Puerto_Escondido_Southern_Mexico-Hotels.html"
scrapy startproject tripadvisor2scrapy genspider review tripadvisor.com 
scrapy crawl tripadvisor -o puerto_escondido_hotels.csv -t csv

#Nombres Columnas puerto_escondido_hotels.csv
Rating
Review


en el repositorio debe haber un README.md con 1. instrucciones claras para instalar y correr su código tal que yo pueda ejecutarlo y 
obtener el resultado del scrapping (p. ej. crea un ambiente de python con este requirements.txt y ejecuta este comando), 
2. formato y estructura del resultado (p. ej. CSV con columnas que se llaman así), 
3. descripción del contenido del sitio web, así como de lo que representan los fragmentos de texto y las categorías en las que está clasificado, 
4. las contribuciones de cada integrante del grupo y 5. cualquier información adicional que consideren importante.
El entregable en Canvas es el link de su repositorio.

