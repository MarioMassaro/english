---
title: "Proyecto de Reconocimiento de Objetos, imágenes y videos"
excerpt_separator: "<!--more-->"
categories:
  - Post Formats
tags:
  - Post Formats
  - readability
  - standard
---

Modelo de detección de objetos a tiempo real

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/ia.jpeg" alt="">
</figure> 

<!--more-->

### Para este proyecto cree una guía personal de como utilizar el modelo Pre-Entrenado de YoloV5
Me vino la necesidad de crear mi propia guía cuando intente hacer mi proyecto y necesite utilizar múltiples videos, blogs y recursos para lograr entender su uso, con esta guía podras aprender a utilizar YoloV5, donde te enseño:

    -Extracción de imágenes (desde el coco dataset y Google imagenes)
    -Renombre de imágenes extraídas
    -División de carpetas (Train, Test, Validation)
    -Tratamiento de imágenes personalizadas para su uso en el modelo (creación de labels)
    -Utilización del modelo y guardado del modelo entrenado para uso futuro

#### Para explicar todo este contenido se creó una carpeta organizada por partes que deberás seguir para hacer tu propio proyecto de detección de objetos

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/machine-1.JPG" alt="">
</figure> 

Dentro de la carpeta podremos encontrar todos los pasos detallados para este proyecto.

### Respecto a la extracción de imágenes

Tenemos dos formas, extrayéndolas de google imágenes con un código que ya tengo creado y explicado que se conecta a la api de Google, o descargamos desde la api del coco dataset

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/machine-2.JPG" alt="">
</figure> 

Es muy fácil de usar y buscar el contenido exacto que necesitas.

### Tratamiento de imágenes y división de entrenamiento, nunca han podido ser más fáciles gracias a roboflow

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/machine-3.JPG" alt="">
</figure> 

Esta página es una completa salvavidas en cuanto a procesado de imágenes, facilita mucho los procesos de encuadrado de imágenes y te ayuda hasta a descargar el formato de las imágenes en formato Yolov5, que esta de más decir que nos facilita aún más la creación de nuestro modelo.

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/machine-4.JPG" alt="">
</figure> 

### Para utilizar el modelo les dejo creado un Google colab con todo el código necesario para su uso

Desde como cargar sus datos a como ver los resultados del modelo.

<figure style="width: 600px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/machine-5.JPG" alt="">
</figure> 

Por último me gustaría que buscaran las reglas básicas de como encuadrar las imágenes, ya que si este proceso se hace erróneamente al menos un poco, el modelo sufrirá en precisión y no sera tan útil como debería, no olviden guardar su modelo al terminar para no tener que entrenar de nuevo, un pickle bastaría.


Muchas gracias por leer este articulo y aquí les dejo el enlace a la guía de mí GitHub para que la puedan probar por ustedes mismos:

  - https://github.com/MarioMassaro/Object-Deteccion-With-Yolo
