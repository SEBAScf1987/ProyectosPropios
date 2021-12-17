## Introducción

[Click aquí para ver el Colab Notebook](https://colab.research.google.com/drive/1JZ4KNNkuTJkueoyC2S5HEqnn1gzATVTd?authuser=2)

Este proyecto en python es inspirado en la clase de Luis Jorge Novelo del curso de Business Intelligence de Platzi.
[Click aquí para ver el proyecto original](https://github.com/PhinanceScientist/AMLO_Wordcloud/blob/master/mexicoPresidentWordCloud.ipynb)

El proyecto trata de la creación de una "nube de palabras" con las palabras encontradas de un discurso del Ex Presidente Evo Morales en Argentina, [Puedes ver el video aquí.
](https://www.youtube.com/watch?v=ZXNFMtlakHo)

### DATA

En el proyecto original del profesor Luis se extrae la información del discurso de la página oficial de Lopez Obrador, sin embargo en el caso de Evo Morales no logré encontrar una página oficial con discursos porque según sé, habla sin algo escrito en muchos discursos, por eso la extracción del texto fue de un video en youtube.

## Metodología

 1. Uso de la librería **youtube-transcript-api** para recopilar el texto generado por los subtítulos en los videos de youtube con python y guardé todo la data en un txt.
 2.  Uso de la librería **wordcloud** en python para replicar la nube de palabras del proyecto original.
	   En este paso se consideró la exclusión de ciertas palabras en    		 "Stopwords" en español que fueron añadidas manualmente para usarlas en el idioma español y tener una mejor respuesta.
	   
