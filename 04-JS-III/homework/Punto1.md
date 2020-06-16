## Array
Una matriz es una variable especial, que puede contener más de un valor a la vez.

```javascript
var carros = ["Saab", "Volvo", "BMW"];
```
Si tiene una lista de elementos (una lista de nombres de automóviles, por ejemplo), el almacenamiento de los automóviles en variables individuales podría verse así:

```javascript
var car1 = "Saab";
var car2 = "Volvo";
var car3 = "BMW";
```
Sin embargo, ¿qué pasa si quieres recorrer los autos y encontrar uno específico? ¿Y si no tuvieras 3 autos, sino 300?

¡La solución es una matriz!

Una matriz puede contener muchos valores con un solo nombre, y puede acceder a los valores haciendo referencia a un número de índice.

## Crear una matriz

El uso de una matriz literal es la forma más fácil de crear una matriz de JavaScript.

Sintaxis:
```javascript
var array_name = [item1, item2, ...];
```
## Acceda a los elementos de una matriz
Accede a un elemento de matriz haciendo referencia al número de índice .

Esta declaración accede al valor del primer elemento en cars:
```javascript
var nombre = carros[0];
```
## Elementos de matriz de bucle
La forma más segura de recorrer una matriz es usando un ciclo for:

```javascript
var frutas, tamanioFrutas;
frutas = ["Banano", "Naranja", "Manzana", "Mango"];
tamanioFrutas = frutas.length;
for (i = 0; i < tamanioFrutas; i++) {
  console.log("Frutas:",frutas[i])
}
```

