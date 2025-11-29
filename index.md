#ALGORITMOS

Un algoritmo es una secuencia de pasos lógicos, en otras palabras, coherentes, ordenados y finitos que se diseñan y utilizan para dar solución a un problema u obtener un resultado esperado.

Los algoritmos deben ser fáciles de entender, sin ambiguedades. Deben ser comprensibles tanto para la persona que lo diseña como para quien lo interpreta. Pero lo más importante es que dicho algoritmo sea comprensible para la máquina que lo ejecutará.

Un algoritmo debe tener siempre un inicio, proceso y fin. Existen algoritmos que solamente realizan acciones y no necesitan ningún dato de entrada externo. La salida sería el proceso como tal. Pero existen otros que sí requieren datos de entrada externos que deben ser procesados ya sea modificados o transformados en una solución que proporcionará datos de salida útiles para el usuario final del software creado. Es un requisito fundamental que los algoritmos sean finitos y resuelvan cualquier problema.

#LENGUAJES DE PROGRAMACIÓN

Un lenguaje de programación como su nombre lo indica es un lenguaje artificial que se utiliza para que el programador de software diseñe instrucciones que serán interpretadas por la máquina para realizar acciones predeterminadas. En palabras más simples, un lenguaje de programación sirve para hablar con la máquina o dispositivo electrónico adaptado para interpretar códigos que él mismo ejecutará, o sea, algoritmos.

#ENTORNOS DE DESARROLLO

Un entorno de desarrollo es un software especial para crear otro software o programas informáticos. Contienen editores de texto donde el programador escribe código utilizando lenguajes de programación y otros complementos como extensiones que facilitan y optimizan el trabajo repetitivo gracias a funciones como autocompletados de expresiones del lenguaje con el que se está trabajando y actualmente inteligencia artificial avanzada que facilita aún más el proceso de programación.

#VARIABLES Y CONSTANTES

En un sistema informático, que como bien sabemos está constituido por hardware y software que interactúan constantemente, existen espacios de memoria donde se almacenan datos temporalmente. Estos datos en el software pueden ser variables o constantes. Los datos variables, como su nombre lo indica, pueden cambiar su valor durante la ejecución de un programa. Los datos constantes no cambiarán su valor durante la ejecución de un programa.

#TIPOS DE DATOS SEGÚN LO QUE REPRESENTAN 

Existen los datos numéricos como los números enteros, números flotantes (decimales), caracteres que representan una letra, un número o un símbolo como una coma o punto entre otros, los datos booleanos que solo arrojan dos valores tales como true o false, falso o verdadero en español, las cadenas de caracteres o strings que se utilizan para representar palabras, números telefónicos, una dirección, entre otros.

#TIPOS DE ACCIONES DE PROCESAMIENTO

En un algoritmo hay procesos que se ejecutan con el objetivo de resolver un problema. Estos procesos pueden ser secuenciales, condicionales o repetitivos. Los secuenciales se caracterizan por seguir instrucciones que se ejecutan una por una sin repetirse automáticamente. Tenemos las acciones condicionales que se valen de estructuras de control o decisión como los if else (si, sino) que realizarán una acción u otra dependiendo de una instrucción que se cumpla o no. También se usan los ciclos o bucles que repetirán procesos un número de veces definidas o siempre y cuando una expresión o instrucción predeterminada se cumpla o no, tales como las estructuras repetitivas for, while y do while en el lenguaje C++.

#OPERADORES

Los operadores sirven para indicar acciones de procesamiento que se deben aplicar a los datos proporcionados, tales como operaciones de comparación, adición, sustracción, asignación, entre otras. Tenemos los operadores aritméticos que se emplean para realizar operaciones matemáticas tales como el símbolo de suma(+), resta(-), residuo(mod, %), entre otros, y los de comparación tales como mayor, menor, igual, menor o igual, mayor o igual y diferente(>, <, ==, <=, >=, !=). Existe un operador de asignación que sirve para almacenar un valor de una variable en otra o directamente que se representa así -> o con el signo igual =.

#ALGORITMO QUE VALIDA EL INGRESO DE UNA PERSONA A UN BAR

~~~
edad = int(input("Ingrese la edad del cliente en dato numérico para validar su entrada al bar: "))

if edad > 17:
    print("Puede ingresar al bar")
else:
    print("No puede ingresar al bar")
~~~
    
#REFLEXIÓN PERSONAL

Los algoritmos no solo existen en el ámbito profesional. La mayoría de las cosas que hacemos a diario como cocinar, bañarnos, comer, ir a trabajar, escribir, hablar, entre otras cosas, siempre siguen una secuencia de pasos ordenados estándar que, aunque pueden variar, siempre tienen algo en común. Ahora, no podemos dirigirnos a una máquina lógica como lo son las computadoras de la misma forma en que interactuamos con un ser humano para darle órdenes. Las máquinas han sido programadas con su propio lenguaje y es necesario comprender cómo funciona para poder crear software eficientemente. Con una máquina hay que ser mucho más específico. Así como los idiomas naturales con los que nos comunicamos tienen reglas que muchas veces ignoramos, los lenguajes de programación también están diseñados con reglas que no podemos darnos el lujo de ignorar. No se nos puede escapar ni siquiera una coma. Gracias a la inteligencia artificial moderna, esto es mucho más fácil.
