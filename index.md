# Diario de Robótica del MOVA

En este diario ire poniendo todos los avances en las prácticas de la asignatura de robotica del Máster de visión de la URJC 

## Sigue líneas

Esta práctica consiste en seguir una línea con un F1 usando visión y un [controlador PID](https://en.wikipedia.org/wiki/PID_controller).

### Primera Versión

En esta primera versión se establecen 2 puntos, uno cerca del horizonte y otro un poco mas abajo, este segundo punto determina la velocidad de giro y con la diferencia entre el primero y el segundo se saca si es una curva recta o una curva.

<iframe width="560" height="315" src="https://www.youtube.com/embed/IjoKkfNpUN4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Segunda Versión

En esta segunda versión se han variado ligeramente los valores de las constantes y de las velocidades máximas para obtener un mejor resultado en la vuelta (más estable)

<iframe width="560" height="315" src="https://www.youtube.com/embed/UKm7d6WgocA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Tercera Versión

En esta tercera versión se ha puesto un punto por encima del horizonte para determinar si hay pared o no, si no la hay estamos en recta. Si la hay en curva. y se toma un punto puy cercano al horizonte para determinar la velcidad de giro

<iframe width="560" height="315" src="https://www.youtube.com/embed/-REtZqYeQUQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


