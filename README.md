# Flappy Bird 

## Procesamiento Digital de Imagenes

## *Integrantes:*
+ Daniel Mosquera Silva  
+ Mary Andrea Doria Gomez

Creacion del Juego Flappy Bird https://www.youtube.com/watch?v=1pdFmtXjYhA
Basado en el Repositorio https://github.com/sourabhv/FlapPyBird

Esta version del juego Flappy Bird Usa la camara para captura los datos y poder controlar el pajaro ,Se utiliza un objeto amarillo para mover el pajaro de arriba hacia abajo(una media movil para el movimiento en Y) y el movimiento en X es fijo. La finalidad de este juego es aplicar los conocimientos adquiridos en procesamiento digital de imagenes en lo que se lleva del curso.

Para poder jugar el juego es necesario la version de Python 3.7 y tener todas las librerias descargadas esto se realiza a traves del comando `pip install XXX(libreria)` en la Terminal del IDE en el cual se hizo la implementacion y por medio de la terminal se ejecuta el comando  `python flappy.py` , este repositorio se puede clonar en cualquier IDE (recomendamos el uso de Visual Studio Code) y se hace a traves del comando `git clone https://github.com/mary-doria/Proyecto1PDI_FlappyBird.git`

### IDE:
* Visual Studio Code 

### Librerias:
+ numpy
+ imutils
+ cv2 
+ pygame 
+ random
+ opencv-python
+ itertools

## **Modo de Uso:**
1. Inicialmente se puede iniciar el Juego con la Tecla Space o UP.
2. Se coloca el objeto frente la camara(Debe ser de color amarillo).
3. Se mueve el objeto de arriba hacia abajo y viceversa para que el pajaro sobrepase los obstaculos.

Sistema de Puntuacion:
* Cada obstaculo que pase el pajaro es un punto y el sistema de puntos funciona como un acumulador hasta que pierda el usuario.

Game Over:
* Si el pajaro se choca contra un obstaculo.


