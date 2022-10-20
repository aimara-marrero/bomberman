# bomberman


## Introducción

El Bomberman es un juego estratégico-laberíntico en el que el 'player' tiene que encontrar la salida. 

Dicha salida, está localizada de forma oculta en un lugar random a lo largo del tablero, en en aquellas casillas en las que se puedan destruir los obstáculos. 

Para la destrucción de obstáculos, bomberman tendrá bombas con las que podrá eliminar dichos obstáculos y salvarse del enemigo. 

Se encontrará tendrá que romper todos aquellos obstáculos en los que se encontrará la puerta. 




# Participantes del desarrollo de juego

* Aimara Marrero      -  GitHub (https://github.com/aimara-marrero)
* Iratze  Eizaguirre  -  GitHub (https://github.com/IraEiza)
* Joseph Vento        -  GitHub (https://github.com/itsJosephV)



# Normas del juego

* El objetivo de bomberman es poder encontrar la puerta de salida. Una puerta que se encuentra de manera aleatoria en nuestro campo de juego. 

* El juego consta de varios elementos:
    - Boundary      --> Las casillas límites que rodean el tablero.
    - Rocks         --> Rocas fijas. Éstas no pueden ser destruidas.
    - Soft-blocks   --> Rocas que bomberman puede destruir.
    - Enemy         --> Nuestro enemigo en el juego. Camina de manera vertical a lo largo del tablero.
    - Salida.       --> Salida generada de manera aleatoria por el tablero y que esta oculta debajo de un "soft-block".

* Comenzaremos nuestra búsqueda con 3 vidas, las cuáles pueden perderse al colisionar con un enemigo, o al estar cerca de una de nuestras bombas durante la explosión

* Contaremos con bombas para poder destruir los obstáculos y eliminar enemigos que encontraremos durante el juego.  

## Cómo se juega

Para que bomberman pueda moverse por el tablero, utlizaremos los siguientes comandos:

* W --> Arriba
* A --> Izquierda
* S --> Abajo
* D --> Derecha
* Space --> Activar bomba



## Debugg

*  Vidas : En ocasiones al ganar la partida con 2 o menos vidas y reiniciar una nueva partida, los iconos de los corazones mantienen el estado de la partida anterior.
* Música de inicio: se inicia de manera aleatoria.
* Bomba: Desactivar más de una bomba a la vez, siempre se elimina la última en ejecutarse. 
* A la hora de poner una bomba en el que el enemigo se encuentre entre el límite inferior y la propia bomba, el enemigo se posiciona en el límite del tablero.



## Enlace al juego

* https://aimara-marrero.github.io/bomberman/

