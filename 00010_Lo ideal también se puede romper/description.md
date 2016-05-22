Como en la definición de `hayBolitasAl` se usa `Mover`, es obvio que hay casos en los cuales podría romperse: basta con posicionar el cabezal en el origen y preguntar si `hayBolitas` de algún color al Oeste.

Pero, ¿no era que las funciones eran **puras** y **no tenían efecto real**? ¿Qué pasa si una función **hace BOOM**?

> Hagamos la prueba: volvé a escribir la función `hayBolitasAl` del ejercicio anterior, esta vez la probaremos con casos donde no pueda moverse el cabezal.