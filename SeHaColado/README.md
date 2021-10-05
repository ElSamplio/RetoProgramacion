# ¡Se ha colado!

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

 La tienda de mi barrio vende a los mejores precios y calidad de la zona, por lo que siempre está llena de gente. Joselito, el dueño, hace tiempo que decidió colocar un expendedor de números para poder atender a los clientes ordenadamente y sin que las discusiones entre ellos perturbasen su quehacer diario. Como no tenía suficiente dinero, no ha podido comprar un contador digital, así que confía en que los propios clientes formen una cola respetando la numeración y no suele pedir el número cuando les atiende; circunstancia que algunos han aprovechado para colarse en numerosas ocasiones.

De este modo, le ha pedido a su hija Claudia que haga una inspección sorpresa diaria. En el momento de la inspección, Claudia les pide a todos los que están en ese momento en la cola que enseñen su número y a los que está segura de que se han colado los expulsa de la tienda. Luego, cuando cierran la tienda, le cuenta a su padre a cuántos ha expulsado ese día.


### _Entrada_

La primera línea contiene un número que indica el número de casos de prueba que aparecen a continuación.

Cada caso de prueba se compone de dos líneas. En la primera aparece un único entero con el número de personas que están en la cola cuando Claudia hace la inspección (entre 1 y 500.000). En la segunda aparecen los números que tienen cada una de esas personas según están en la cola, números entre 1 y 106, todos distintos (nadie ha llegado aún hasta el extremo de falsificar los números). Eso sí, pueden faltar números, porque hay personas que ya han sido atendidas o personas que se cansaron de esperar y se marcharon.

### _Salida_

Para cada caso de prueba, el programa escribirá el número de personas que Claudia ha expulsado.

### _Ejemplo de entrada_

```sh
2
5
2 3 6 7 9
7
1 4 3 2 5 7 6
```

### _Ejemplo de salida_

```sh
0
3
```