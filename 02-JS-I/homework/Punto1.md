## Variables

Una variable es una unidad de datos con nombre a la que se le puede asignar un valor . Si se modifica el valor, el nombre no cambia.

Algunas variables son mutables , lo que significa que sus valores pueden cambiar. Otras variables son inmutables , lo que significa que su valor, una vez asignado, no se puede eliminar ni alterar.

##  String

Se utiliza para representar texto en lugar de números. Se compone de un conjunto de caracteres que también pueden contener espacios y números. Por ejemplo, la palabra "hamburguesa" y la frase "Comí 3 hamburguesas" son dos cadenas. Incluso "12345" podría considerarse una cadena, si se especifica correctamente. Por lo general, los programadores deben incluir cadenas entre comillas para que los datos se reconozcan como una cadena y no como un número o nombre de variable.

## Funciones (argumentos, `return`)

En matemáticas, una función se define como una relación entre valores definidos y una o más variables. Por ejemplo, una función matemática simple puede ser:

> y = 2x

Las funciones de la computadora son similares a las funciones matemáticas en el sentido de que pueden hacer referencia a parámetros , que se pasan o ingresan en la función. Si el ejemplo anterior se escribiera como una función de computadora, "x" sería el parámetro de entrada e "y" sería el valor de salida resultante . Podría verse más o menos así:

```javascript
    function nombre(x) {
      var y = 2 * x;
      return y;
    }
```
En este ejemplo, la relación de y con x es que y es el doble del valor asignado a x. Si bien las funciones matemáticas pueden ser mucho más complejas que esto, la mayoría son simples en relación con las funciones utilizadas en la programación de computadoras. Esta puede ser la razón por la cual las funciones matemáticas a menudo se denominan "expresiones", mientras que las funciones de la computadora a menudo se llaman "procedimientos" o "subrutinas".
El ejemplo anterior es una función muy básica. La mayoría de las funciones utilizadas en los programas de computadora incluyen varias líneas de instrucciones e incluso pueden hacer referencia a otras funciones.

Le siguen un par de paréntesis que, opcionalmente, pueden contener valores pasados ​​a la función. Estos valores se llaman _argumentos_ . No todas las funciones presentan argumentos. Luego vienen los corchetes y las declaraciones que ayudan a la función a hacer lo suyo.

## Declaración if

La`if(...)`declaración evalúa una condición entre paréntesis y, si el resultado es `true`, ejecuta un bloque de código.

Por ejemplo:

```javascript
let anio = prompt('¿En que se año aparecio JavaScript', '');

if (anio == 1995) alert( 'Excelente!' );
```

En el ejemplo anterior, la condición es una simple verificación de igualdad `(anio == 1995)` , pero puede ser mucho más compleja.

Si queremos ejecutar más de una declaración, tenemos que envolver nuestro bloque de código dentro de llaves:

```javascript
if (anio == 1995) {
  alert( "Excelente!" );
  alert( "Eres muy inteligente!" );
}
```
Recomendamos envolver su bloque de código con llaves `{}`cada vez que use una `if`instrucción, incluso si solo hay una instrucción para ejecutar. Hacerlo mejora la legibilidad.

## Valores booleanos

Muy a menudo, en la programación, necesitará un tipo de datos que solo puede tener uno de dos valores, como

-   SÍ NO
-   ENCENDIDO APAGADO
-   VERDADERO FALSO

Para esto, JavaScript tiene un tipo de datos **booleanos** . Solo puede tomar los valores **true** o **false** .