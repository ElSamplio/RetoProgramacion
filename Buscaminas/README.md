# Buscaminas

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

¿Has jugado alguna vez buscaminas? Este pequeño y lindo juego viene con cierto sistema operativo cuyo nombre no podemos nombrar ahora ;). La meta del juego es encontrar dónde están localizadas todas las minas dentro de un campo de M x N cuadros.
El juego muestra un número en un cuadro el cual te dice cuántas minas hay en los cuadros adyacentes a ese cuadro. Cada cuadro tiene a lo sumo ocho cuadros adyacentes. 
La representación del campo de 4 x 4 en la izquierda contiene dos minas, cada una representada por un asterisco (*). Si representamos el mismo campo con los números que indican la cantidad de minas adyacentes, obtendríamos los valores a la derecha:


```sh
*...	*100
....	2210
.*..	1*10
....	1110
```

### _Entrada_

La entrada consistirá en un número arbitrario de campos. La primera línea de cada campo contiene dos enteros n y m (0 <n,m<= 100) que indica el número de filas y columnas del campo, respectivamente. Cada una de las filas n siguiente contiene exactamente m caracteres, representando el campo.
Los cuadros seguros están denotados por “.” y los cuadros con minas por “*”, ambas sin las comillas. La primera línea de entrada donde n = m = 0 representa el final de la entrada y no debe ser procesada.

### _Salida_

Para cada campo, imprime el mensaje Field#x: en una línea sola, donde x indica el número del campo iniciando por 1. Las n líneas siguientes deben contener el campo con los caracteres “.” Reemplazados por el número de minas adyacente a ese cuadro. Debe haber una línea en blanco entre las salidas de cada campo.

### _Ejemplo_

El siguiente es un ejemplo de entradas y la respectiva salida esperada

```sh
   Muestra de entrada    |    Muestra de salida
   4 4                   |    Field #1:
   *...                  |    *100
   ....                  |    2210
   .*..                  |    1*10
   ....                  |    1110
   3 5                   |    Field #2:
   **...                 |    **100
   .....                 |    33200
   .*...                 |    11110
   0 0                   |
```