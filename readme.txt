
#Tarea #1 Grupo: Franz Heidacher, Jaime Garcia y Victor de Leon
#Grupo NLP 7:
#Curso Text Minning UVG
#Catédratico: Pedro Aguilar.

#Se creó environment scrapping-tripadvisor en Anaconda llamado scrapping-tripadvisor
#Se instaló scrapy con pip install scrapy
#Se aperturó terminal para envío de comandos scrapy (scrapy shell, scrapy startproject, scrapy genspider, scrapy crawl)

#Se editó en editor de texto (notepad) los archivos .py para configuración y edición de spider.py

#Comandos específicos utilizados
C:\Users\vdeleon\Anaconda3\envs\tripadvisor2>scrapy shell "https://www.tripadvisor.com/Hotels-g153373-Puerto_Escondido_Southern_Mexico-Hotels.html"
scrapy startproject tripadvisor2scrapy genspider review tripadvisor.com 
scrapy crawl tripadvisor -o puerto_escondido_hotels.csv -t csv

#Nombres Columnas del output puerto_escondido_hotels.csv
Rating
Review

#El sitio que se utilizó fue el de Tripadvisor y se replicó el ejercicio realizado en clase. Usando la referencia de Hoteles específicamente los ubicados en Puerto Escondido México. Aporte completo de cada integrante en la tarea presentada. Contribuciones individuales de cada integrante del grupo: Victor De León, ejecutó y compiló finalmente el código desde su computadora; usando la librería de scrapy. Jaime García, ejecutó y compiló usando Jupiter notebook usando un ejemplo visto en internet donde se utilizaban las librerias selenium y Beautifulsoap. Franz Heidacher, soporte para la creación de cuentas en Github del resto del grupo, creación del repositorio que se utiliza para entregar la tarea.   

