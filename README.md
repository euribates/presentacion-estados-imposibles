# Charla Estados imposible

## Título

Estados imposibles (Y como eliminarlos)


_Making impossible states unrepresentable_ es un principio de diseño que
suele usarse en lenguajes con tipado de datos fuerte, pero que puede
aplicarse igualmente a cualquier lenguaje, estructura de datos o base de
datos. La idea es reducir los estados en los que pueden estar nuestros
datos, idealmente haciendo imposible representar estados inválidos.

Si conseguimos esto, no solo reducimos el número de estados (Lo que ya
de por si es beneficioso), también reducimos o eliminamos los estados
conflictivos, lo que es aun mejor. El sistema no tiene que ocuparse de
manejar estos estados, porque nunca se los va a encontrar. Hemos hecho
**literalmente imposible** que estos errores se presenten en el sistema.

Veremos varios ejemplos de código Python que inicialmente permiten la
representación de estados imposibles, y lo modificaremos para
eliminarlos. Estos ejemplos pretenden mostrar como una mejora
relativamente simple puede traducirse en una simplificación drástica del
sistema.

En resumen, veremos la importancia de realizar un análisis previo sobre
los estados de nuestros datos, para determinar si permiten representar
estados imposibles. Si es el caso, estudiar la posibilidad de usar
representaciones alternativas que los eliminen.  Esto presenta ventajas
como la reducción de la complejidad del sistema, del código, de los
tests y del tratamiento de excepciones, entre otras. 


## Resumen

Conviene echar una pensada sobre los
estados y ver si podemos representar
Cualquier conjunto de datos
interrelacionados son un estado
La representación de un objeto “real” no
tiene por que seguir su estructura “fisica”

## Ejemplos

https://geeklaunch.io/blog/make-invalid-states-unrepresentable/

https://inside.java/2024/06/03/dop-v1-1-illegal-states/

