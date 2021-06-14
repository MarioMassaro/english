---
title: "Pythoneer"
excerpt_separator: "<!--more-->"
categories:
  - Post Formats
tags:
  - Post Formats
  - readability
  - standard
---

Pythoneer "Nuestra librearia dedicada a la Ciencia de Datos"

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/pytho.jpeg" alt="">
</figure> 

<!--more-->

### Esta libreria fue creada para facilitar el proceso de limpieza de datos y su visualizacion, para instalarla utilizamos "pip install pythoneer"

Algunas funciones como las de machine learning siguen en desarrollo pero las funciones de limpieza de datos, como el KNN, One Hot Encoders entre muchos otros son 100% funcionales. Las funciones de visualizacion tambien estan operativas y explicadas en el repositorio por si quieren entender su funcionamiento.

#### esta libreria utiliza por detras:

	-Pandas
	-Numpy
	-Seaborn
	-Matplotlib
	-Plotly
	-Scipy
	-Sklearn

#### Un pequeño ejemplo de como utilizar esta libreria

primero debemos instalarla e importarla

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/pytoneer-1.JPG" alt="">
</figure> 

observamos nuestro dataframe y vemos como esta compuesto y que fallos tiene

<figure style="width: 400px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/pythoneer-2.JPG" alt="">
</figure> 

como podemos ver tiene dos columnas vacias y otras dos columnas con menos de 1/3 del contenido que deberia tener. Usemos una de las funciones basicas de nuestra libreria para hacer una limpieza rapida y ver como queda el dataframe anterior.

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/pythoneer-3.JPG" alt="">
</figure> 

completamente limpio y listo para usar, es una funcion un poco fuerte o de uso rapido, no es recomendable usar esa funcion para un trabajo detallado pero para este ejemplo entra perfectamente, elimina las columnas con menos de 30% de contenido por defecto, pero ese valor se le puede poner a mano para hacerla mas detallada.

#### Probemos otra funcion una de visualizacion esta vez. 

<figure style="width: 800px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/pythoneer-4.JPG" alt="">
</figure> 

ahora veamos el resultado de poner esta funcion simple con la unica variable del dataframe, tiene muchas otras pero como dije mantengamoslo simple en esta demostracion.

<figure style="width: 400px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/pythoneer-5.JPG" alt="">
</figure> 

con esta pequeña funcion podemos rapidamente la relacion entre la variables contenidas en el dataframe sin mucho esfuerzo, ahora si utilizaramos otras variables podriamos detallarlo un poco mas y hacerlo mucho mas preciso. Esa es la utilidad de esta libreria y aun le queda bastante tiempo para mejorias que haremos mientras las vayamos necesitando.

#### La documentacion completa esta en mi repositorio de git:
    -https://github.com/MarioMassaro/Pythonners-Proyecto-Conjunto

#### De ser necesario se me puede encontrar al final de la descripcion como uno de los autores, junto con mi perfil de linkedin