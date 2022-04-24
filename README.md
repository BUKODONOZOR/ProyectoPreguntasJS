# ProyectoPreguntasJS

![image](https://user-images.githubusercontent.com/90481288/164972635-57488321-b905-42ae-b217-321253f1ab28.png)


index.html: En este archivo se encuentran varios div (puntaje, dificultad,encabezado,categoria, numero, pregunta, imagen, btn) que son las etiquetas que son sujetas a cambios, todas estas etiquetas están dentro de un contenedor, de igual manera podemos ver una división [<Style>] que contiene los estilos de cada uno de los elementos .
![image](https://user-images.githubusercontent.com/90481288/164972626-d6ff0251-2897-40ab-957f-68a9de27796c.png)
![image](https://user-images.githubusercontent.com/90481288/164972643-a08149c3-aef1-421d-9b1b-f16fb1d8737e.png)



index.js: El código en JavaScript está dividido en una serie de funciones que le dan la lógica a la aplicaciones:
![image](https://user-images.githubusercontent.com/90481288/164972619-e2c4368a-f73c-4ea1-950a-a43ff633d04a.png)


escogerPreguntaAleatoria : genera un número aleatorio basándose en el tamaño del archivo JSON ,tiene un condicional donde se selecciona a cuál de los archivos Json se debe acceder dependiendo del nivel de dificultad en el que se encuentre el jugador. También incluye un ciclo que depende la ejecución del juego, dentro de este , se puede ver el condicional que determina si el jugador ganó el juego 


escogerPregunta: Se encarga de pintar cada una de las etiquetas con los valores correspondientes de la pregunta ,esto con palabras claves como: selec_id, InnerHTMl, stlye.


oprimir_btn: Esta incluida la lógica que determina si una pregunta es correcta y utilizando .style pintar el botón, agregar puntos y pasar a la siguiente página. 

desordenarRespuestas: Para aumentar la dificultad , utilizando el .Math se desordenan las preguntas aleatoriamente . 


RECOMENDACIONES

Ejecutar en el navegador (preferiblemente actualizado )  utilizando la extensión live server 

![Uploading image.png…]()
