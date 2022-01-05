# Kroak

## Funcionalidades implementadas:
- 5 niveles que se completan llevando a ambas ranas (los personajes jugables) a sus respectivas banderas.
- Ambos personajes se ven afectados por las teclas izquierda y derecha y el salto de la rana roja (personaje que se encuentra en la parte de abajo) está invertido. Las colisiones de ambos personajes son independientes entre sí.
- Cuando la rana verde (personaje de arriba) cae más allá de la linea roja (saliendo de su mundo), ésta activa su animación de muerte y se reinicia el nivel. Lo mismo sucede a la inversa con la rana de abajo.
- Se han implementado botones y barreras, una caja movible y unos pinchos (verdes para la rana roja y rojos para la rana verde), que se han usado en mínimo un nivel (combinando sus respectivas mecánicas en la mayoría de niveles).
- El nivel hace scroll siguiendo el movimiento de la rana, para visualizar los niveles que són más grandes que la ventana del juego.
- El juego cuenta con diversas teclas para saltar el contenido, que se explicarán en detalle en la parte posterior (ver apartado Instrucciones)
- El juego cuenta con pantalla de título principal, pantalla de créditos y instrucciones integradas en el propio juego (por decisión estética y debido a la simplicidad de los controles).
- Diferentes canciones para las distintas pantallas y niveles.
- Diferentes efectos de sonido para las diferentes entidades del juego.
- Animaciones personalizadas para todas les entidades del juego y sus diferentes interacciones.
- 1 nivel extra que se completa aplicando una nueva funcionalidad. En este nivel se deben recoger las 8 luciérnagas repartidas por el nivel (4 para cada rana) antes de que se acabe el tiempo (contador presente en pantalla) para completar el nivel. Además, este nivel cuenta con una pantalla extra animada que aparece cuando se termina el tiempo y no se han acabado de recoger todas las luciérnagas.

## Instrucciones del juego:
- Flecha izquierda:	Movimiento hacia la izquierda
- Flecha derecha: 	Movimiento hacia la derecha
- Flecha arriba:		Salto
- Escape:			Cerrar juego
- Enter:			Avanza ciertas pantallas (especificadas dentro del juego)

#### Teclas especiales:
- F1:			Salta al nivel número 1
- F2:			Salta al nivel número 2
- F3:			Salta al nivel número 3
- F4:			Salta al nivel número 4
- F5:			Salta al nivel número 5
- F6:			Salta al nivel número 6
- F7:			Salta a la pantalla créditos
- F8:			Destruye todas las barreras del nivel en el que te encuentres
- F9:			Activa el Godmode (evita la muerte por pinchos, haciendo que los atravieses)
- F10:			Salta a la pantalla especial del nivel 6, que aparece cuando te quedas sin tiempo
- F11:			Recoge todas la luciérnagas (si te encuentras el el nivel 6), completando el nivel

## Contenido del repositorio:

- ***Carpeta Binario***
	Ejecutable del juego con todos los recursos necesarios para ser ejecutado desde cualquier ordenador.

- ***Carpeta Proyecto***
	Carpeta que contiene el proyecto de Visual Studio con el código fuente compilable.

- ***demo.avi***
	Video demostración de 1 minuto donde se ven las funcionalidades principales del juego.

## Creadores:
- Toni García
- Moisés Campillo
