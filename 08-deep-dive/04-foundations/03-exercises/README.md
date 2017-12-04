# Retos de código

* Tipo: `practice`
* Formato: `self-paced`
* Duración: `30min`

***

## Objetivos

Practicar los conceptos revistados en esta unidad a través de los siguientes
retos de código:

### [1. Potencia de 2](00-power-of-two)

Calcula la potencia de 2 elevado a un número específico. Debes de usar un loop
(no `Math.pow()`).

Ejemplo:

```javascript
const output = powerOfTwo(10);

console.log(ouput); // -> 1024
```

### [2. Invertir un arreglo](01-reverse)

Usar estructuras de control para invertir un arreglo de números. Como entrada
recibirás un arreglo de números u objetos y como salida se espera un arreglo con
el orden invertido de los elementos.

> No es válido usar `arr.reverse()`.

Ejemplo:

```javascript
const output = reverse([1, 2, 3, 4]);

console.log(ouput); // -> [4, 3, 2, 1]
```

### [3. Contador de propiedades](02-object-properties-counter)

Dado un objeto como parámetro, contar la cantidad de propiedades que este
contiene y retornarlo.

Ejemplo:

```javascript
const output = objectPropertiesCounter({ 'name': 'John', 'lastname': 'Doe' });

console.log(ouput); // -> 2
```

### [4. Montos sin moneda](03-currency-amount)

Dado un arreglo de montos en distintas monedas, retornar solo los valores sin
importar la moneda.

> Las monedas participantes solo son pesos chilenos ($ CLP), pesos mexicanos
> ($ MXN) y soles (S/. PEN).

Ejemplo:

```javascript
const output = currencyAmount([ '$ 600 CLP', '$ 1000 MXN', 'S/. 200 PEN' ]);

console.log(ouput); // -> [ 600, 1000, 200 ]
```

> **Hint:** Revisa sintaxis de [expresiones regulares](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp)
así como [RegExr](https://regexr.com/) para ayudarte a construir la expresión
regular.
