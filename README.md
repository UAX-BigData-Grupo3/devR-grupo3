# Grupo 3 del Master de Big data de la UAX

### ***Componentes***

* Paula González Mataix
* Cristian Sales Villa
* Rafael Castillo García
* Diego Cristóbal Herreros

## Desarrollo del trabajo

Esta práctica se desarrolla en 3 partes, todas ellas implementadas en un fichero Rmarkdown accesible desde [aqui](https://uax-bigdata-grupo3.github.io/devR-grupo3):

### Primera parte

Script del preprocesado del dataframe del [Titanic](https://www.kaggle.com/competitions/titanic/data?select=train.csv)

### Segunda parte

Presentación de varias funciones del paquete **Text Mining**

### Tercera parte

Consiste en seleccionar un dataframe y hacer un estudio y presentación de los datos. En nuestro caso, hemos elegido uno sobre el **cáncer de pecho**.


## Detalles de la práctica

* *Buenas prácticas en R* -> Hemos implementado una pipeline con un lint muy riguroso para obligarnos a aplicarlas. [Ejemplo](https://github.com/UAX-BigData-Grupo3/devR-grupo3/actions/runs/4036589290/jobs/6939288362#step:5:14)

* *Comentarios* para facilitar la comprensión del código -> hemos añadido comentarios y explicaciones con markdown en cada proceso.

* *Ejecución sin errores* -> al tener una pipeline para el renderizado del fichero Rmd, posterior exportación y subida a Github Pages, nos aseguramos de que con cualquier error nos saltaría la pipeline.

* *Valoración positiva del uso de Rmarkdown* -> hemos estado trabajando con Rmarkdown durante todo el proceso y nos hemos familiarizado con la interfaz. 

* *Uso de librería data.table* -> hemos usado alguna función como fread para la carga de los csv.

* Hemos versionado el código usando para ello una pipeline para crear la release correspondiente cada vez que se hacia un merge desde una Pull Request. Ejemplo de [release](https://github.com/UAX-BigData-Grupo3/devR-grupo3/releases/tag/0.0.7)