# Conceptos Básicos


## Javascript

**Javascript** es un lenguaje de programación que corre del lado del navegador, es decir, del lado del usuario, es un lenguaje de tipado dinámico (no se necesita declarar el tipo de dato). Este lenguaje presenta conceptos como:


* **Variables**
  * Son elementos que pueden reservar un espacio en la memoria para almacenar un dato de cualquier tipo, ya sea numérico, texto, númerico con coma flotante, booleano (true / false), etcétera.
* **Strings**
  * Es el término en inglés para referirse a la Cadena de Caractéres, texto que va desde letras hasta símbolos especiales como el "@" (arroba), o el "&" (ampersand).
* **Funciones (argumentos,** return **)**
  * Las funciones son procesos definidos para llevar a cabo alguna tarea en específico, suelen recibir **argumentos** y pueden **retornar** (return) algún valor o bien pueden no retornar ninguno. los argumentos son variables que la función requiere para poder llevar a cabo el proceso deseado, el return nos entrega el resultado de ese proceso, un ejemplo es la función *suma()*.

    `function suma(x, y) {return x + y;}`
  * La función sumará los argumentos "x" y "y", el resultado será devuelto con "return".
* **Declaraciones (**if**)**
  * **if** es una declaración condicional, es decir, ejecutará algún proceso en caso de cumplirse alguna condición lógica, por ejemplo:

    `if (x > 1) {return "La condición es verdadera"} else {return "La condición es falsa"}`
  * La declaración condicional también tiene la facultad de ejecutar código en caso de que alguna condición sea falsa, a esta estructura se le conoce como: if-else.
* **Valores Booleanos**
  * Los valores booleanos son aquellos que se devuelven en las declaraciones condicionales, este tiene únicamente dos resultados posibles:
    * Verdadero (true).
    * Falso (false).
  * Estos valores se usan para la lógica (como se describió anteriormente) y son también para otras estructuras que veremos más adelante.
