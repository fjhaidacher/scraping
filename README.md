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

#Columnas puerto_escondido_hotels.csv ->
Rating
Review
