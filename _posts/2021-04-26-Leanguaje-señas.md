---
title: "Reconocedor de Lenguaje de señas"
excerpt_separator: "<!--more-->"
categories:
  - Post Formats
tags:
  - Post Formats
  - readability
  - standard
---

En este proyecto creo una red neuronal con deep learning para predecir palabras a través de imágenes con lenguaje de señas. Este fue una de mis competiciones de Kaggle en la que quede de segundo y aquí comparto su código.

<figure style="width: 400px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/señas.jpg" alt="">
</figure> 

<!--more-->
## Con una precisión del 90% como podrán ver.

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/colega.JPG" alt="">
</figure> 

TTodos los procedimientos se pueden descargar desde mi repositorio, si quieres intentarlo por tu cuenta los datos utilizados para el train y test se pueden encontrar en el kaggle "que dices colega?", si necesitas el link puedes encontrarlo en el repositorio.

El dataframe original son solo 2 columnas, la ubicación de la imagen y el target o significado de la seña.

<figure style="width: 300px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/señas-df-1.JPG" alt="">
</figure> 

También para aumentar las probabilidades de aprendizaje usamos un generador de imágenes, lo que modifica la misma imagen de formas distintas para crear más contenido de entrenamiento.

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/generador-extra.JPG" alt="">
</figure>

Y al momento de tenerlo todo dividido y tratado pasamos a crear nuestra propia red neuronal con keras y 29 capas de salida, ya que habían 29 targets en el dataframe original.

 <figure style="width: 900px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/red-neuronal.JPG" alt="">
</figure>

### Este notebook se puede encontrar en el apartado de mi git Sordo_Mudo:
	-https://github.com/MarioMassaro/Notebooks