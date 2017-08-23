# Funciones

* Formato: `lectura`
* Duración: `Xmin`

***

Las funciones son bloques de construcción de aplicaciones que engloban múltiples
sentencias de código. Son particularmente importantes en JavaScript porque
soporta características como `first-class functions`, `functions as objects`,
`runtime function definition` y más que veremos en esta lección.

A continuación, se listan algunos principios que te ayudarán escribir mejores
funciones:

* **Don't Repeat Yourself (DRY)**: Es muy común que a lo largo del desarrollo de
una solución nos encontremos con un patrón que se va repitiendo a lo largo de
nuestro código. Una vez identificado un patrón, es tiempo de escribir una
función, objeto o módulo que encapsule dicho patrón para que sea fácilmente
reusable. Esto ayuda también a que si encontramos algún bug o quisiéramos
agregar funcionalidad, solo se tendría que hacer en un lugar. Además,
escribiendo una función reusable te obliga a aislar el patrón del problema, lo
cual ayuda a tener funcionalidad relacionada de manera agrupada.

* **Do One Thing (DOT)**: Cada función debe hacer solo una cosa y hacerlo lo
mejor posible. Siguiendo este principio hará tu función más reusable, legible y
fácil de depurar.

* **Keep It Simple Stupid (KISS)**: Los programadores a menudo son tentados de
llegar con soluciones asombrosas. Obviamente, esto es bueno, pero a veces, los
programadores son muy sabios y las soluciones parecen encriptadas. Esto suele
suceder cuando una sola línea de código es usada para lograr el objetivo de más
de un simple problema.

* **Less Is More**: Para alcanzar la mayor legibilidad posible y reducir la
tentación de hacer más de una cosa, las funciones deben ser tan cortas como sea
posible. Si la función se vuelve muy extensa, es bueno considerar separarlo en
subtareas y datos a lo largo de funciones y objetos.

***
