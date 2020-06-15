# Operadores logicos
Hay tres operadores lógicos en JavaScript: `||` (ó), `&&`(y), `!`(no).

Aunque se llaman "lógicos", se pueden aplicar a valores de cualquier tipo, no solo booleanos. Su resultado también puede ser de cualquier tipo.

## || (O)

El operador "OR" se representa con dos símbolos de línea vertical:

    var resultado = a || b;

En la programación OR lógico está destinado a manipular solo valores booleanos. Si alguno de sus argumentos es **true**, regresa **true**, de lo contrario, regresa **false**.

```javascript
alert( true || true );   // true
alert( false || true );  // true
alert( true || false );  // true
alert( false || false ); // false
```
## && (AND)
El operador AND se representa con dos símbolos de unión `&&`:

    var resultado = a && b;

En la programación AND lógico está destinado a manipular solo valores booleanos. Si  todos sus argumentos son **true**, regresa **true**, de lo contrario, regresa **false**.

```javascript
alert( true&& true );   // true
alert( false && true );  // false
alert( true && false );  // false
alert( false && false ); // false
```

## ! (NOT)

El operador booleano NOT se representa con un signo de exclamación `!`.

La sintaxis es bastante simple:

```javascript
resultado = !value;
```

El operador acepta un único argumento y hace lo siguiente:

1.  Convierte el operando a tipo booleano: `true/false`.
2.  Devuelve el valor inverso.

Por ejemplo:

```javascript
alert( !true ); // false
alert( !0 ); // true
```
