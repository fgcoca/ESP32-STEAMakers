# <FONT COLOR=#8B008B>Operadores en programación C++</font>

## <FONT COLOR=#007575>**¿Que es un operador?**</font>
En general se puede decir que un operador es un elemento de programa que se aplica a uno o varios operandos en una expresión o instrucción. Existen muchos tipos de operadores y nosotros vamos a mostrar aquí solamente algunos de los mas utilizados. Los mostraremos por tipos como sistema para clasificarlos.

## <FONT COLOR=#007575>**Operadores de asignación**</font>
Sirven para asignar un valor especifico a una variable mediante asignación simple o por dos operadores. En la tabla siguiente vemos algunos de estos operadores:

<center>

| Operador | Nombre | Sintaxis |
|:|---|---|
| = | Asignación | a = b |
| += | Suma y asignación | a += b; a = a + b |
| -= | Resta y asignación | a -= b; a = a - b |
| *= | Multiplicación y asignación | a *= b; a = a * b |
| /= | División y asignación | a /= b; a = a / b |
| ++ | Posincremento o preincremento | a++ ; ++a |
| -- | Posdecremento o predecremento | a-- ; --a |

</center>

## <FONT COLOR=#007575>**Operadores Aritméticos**</font>
Nos permiten hacer operaciones o cálculos simples. Los vemos en la tabla siguiente:

<center>

| Operador | Nombre | Sintaxis |
|:|---|---|
| + | Suma | a + b |
| - | Resta | a - b |
| * | Multiplicación | a * b |
| / | División | a / b |
| % | Módulo o resto de división | a % b |
| ++ | Incremento en 1 | a++; a = a+1 |
| -- | Decremento en 1 | a--; a = a-1 |

</center>

## <FONT COLOR=#007575>**Operadores Relacionales o de comparación**</font>
Sirven para comparar dos variables o expresiones o bien probar la veracidad de una condición. La respuesta es tipo booleano (falso = 0 y verdadero = 1). Los vemos en la tabla siguiente:

<center>

| Operador | Nombre | Sintaxis |
|:|---|---|
| < | Menor que | a < b |
| > | Mayor que | a > b |
| <= | Menor o igual que | a <= b |
| <= | Mayor o igual que | a >= b |
| == | Igual | a == b |
| != | Distinto | a != b |

</center>

## <FONT COLOR=#007575>**Operadores lógicos**</font>
Siempre generan un resultado de tipo booleano y se corresponden con la idea de funcionamiento de las tablas de verdad de la puertas lógicas elementales. En la tabla siguiente se dan las tablas de verdad y los operadores.

<center>

| a | b | AND | OR | NOT a | NOT b | Operador | Nombre | Sintaxis |
|:|:|:|:|:|:|:|---|---|
| 0 | 0 | 0 | 0 | 1 | 1 | | | |
| 0 | 1 | 0 | 1 | 1 | 0 | && | Y lógico-AND | a&&b |
| 1 | 0 | 0 | 1 | 0 | 1 | || | O lógico-OR | a||b |
| 1 | 1 | 1 | 1 | 0 | 0 | ! | Negación lógica-NOT | !a |

</center>

Existen otros muchos operadores que se pueden consultar en la web.
