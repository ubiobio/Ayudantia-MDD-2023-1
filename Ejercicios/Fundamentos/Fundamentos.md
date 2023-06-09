## Listado de ejercicios para practicar los fundamentos de la programacion y JS

### Variables, tipos de datos primitivos y operadores aritmeticoss
_[Documentacion en este repositorio](../../JavaScript/Fundamentos/VariablesYTipos/variablesYTipos.md)_

#### Ejercicios 1 ( Varibles y tipos de datos)

- Declara una variable o constante llamada nombre y asígnale un valor de tipo cadena.
- Declara una variable o constante llamada edad y asígnale un valor numérico.
- Declara una variable o constante llamada puedoConducir y asígnale un valor booleano.
- Para cada variable o constante, imprime en consola el tipo de dato y el valor que contiene.

#### Tips:
  - Para imprimir en consola puedes usar `console.log()`, por ejemplo:
      ```js
        const nombre = 'Juan'
        console.log(nombre) // En consola: Juan
      ```

  - Existe un operador en JS que nos dice cual es el tipo de dato de la variable: `typeof`
    - Ejemplo:
      ```js
         const nombre = 'Juan'
         console.log(typeof nombre) // En consola: string
      ```
- Documentacion oficial: https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Operators/typeof

#### Ejercicios 2 ( Operadores aritmeticos )

- Dado los siguientes valores numericos:
  ```js
    const numero1 = 10
    const numero2 = 20
    ```
    - Imprime en consola el resultado de las siguientes operaciones:
    - Suma
    - Resta
    - Multiplicacion
    - Division
    - Modulo
    - Exponente
    - Incremento
    - Decremento

#### Tips:
  - Pueden declarar una variable para guardar el resultado de cada operacion y luego imprimirlo en consola.
  - Pueden usar directamente `console.log()` para imprimir en consola el resultado de cada operacion.
  - Ejemplos:
    ```js
      const numero1 = 10
      const numero2 = 20
      const suma = numero1 + numero2
      console.log(suma) // En consola: 30

      const numero1 = 10
      const numero2 = 20
      console.log(numero1 + numero2) // En consola: 30
    ```

#### Ejercicios 3 ( Operadores de asignacion y comparacion )

- Dado los siguientes valores numericos:
  ```js
    let numero1 = 13
    const numero2 = 15
    const numero3 = '13' 
    ```
    - Crear una variable nueva y asignarle el valor de numero1 o numero2 y mostrar por consola.
    - Muestre por consola si el numero1 es mayor o igual que numero2.
    - Muestre por consola si el numero1 es menor o igual que numero2.
    - Muestre por consola si el numero1 es menor que numero3.
    - Muestre por consola si el numero1 es igual que numero3.
    - Muestre por consola si el numero1 es diferente que numero2.
    - Muestre por consola si el numero1 es estrictamente igual que numero3.
    - Muestre por consola si el numero1 es estrictamente diferente que numero3.

#### Tips:
  - Recordar la diferencia entre `==` y `===`

## Estructuras de control
_[Documentacion en este repositorio](../../JavaScript/Fundamentos/EstructurasDeControl/estructurasDeControl.md)_
#### Ejercicios 4 ( Condicionales )

- Dado los siguientes valores numericos:
  ```js
    const numero1 = 10
    const numero2 = 20
    const numero3 = 30
    ```
    - Imprimir en consola el número mayor de los tres.
    - Imprimir en consola el número menor de los tres.
    - Imprimir en consola si el numero1 es par o impar.
    - Imprimir en consola si el numero2 es par o impar.
    - Imprimir en consola si el numero3 es par o impar.
    - Imprimir en consola si el numero1 es multiplo de 5.
    - Imprimir en consola si el numero2 es multiplo de 5.
    - Imprimir en consola si el numero3 es multiplo de 5.

#### Tips:

  - Usar el if como en el siguiente ejemplo:
    ```js
    const numero1 = 30
    const numero2 = 20
    
    if (numero1 > numero2) {
      console.log('numero1 es mayor que numero2')
    }
    ```
  - Tambien se pueden encadenar if, else if y else:
    ```js
    const numero1 = 30
    const numero2 = 20
    
    if (numero1 > numero2) {
      console.log('numero1 es mayor que numero2')
    } else if (numero1 < numero2) {
      console.log('numero1 es menor que numero2')
    } else {
      console.log('numero1 es igual que numero2')
    }
    ```

#### Ejercicios 5 ( Ciclos )

- Dado los siguientes valores numericos:

    - Imprimir en consola los numeros del 1 al 10.
    - Imprimir en consola los numeros del 10 al 1.
    - Imprimir en consola los numeros del 1 al 10 pero solo los pares.
    - Imprimir en consola los numeros del 1 al 10 pero solo los impares.
    - Imprimir en consola los numeros del 1 al 10 pero solo los multiplos de 3.
    - Imprimir en consola los numeros del 1 al 10 pero solo los multiplos de 5.
    - Imprimir en consola los numeros del 1 al 10 pero solo los multiplos de 3 y 5.
    - Imprimir en consola los numeros del 1 al 10 pero solo los multiplos de 3 o 5.

#### Tips:

- Usar el for como en el siguiente ejemplo:
  ```js
  for (let i = 0; i < 10; i++) {
    console.log(i)
  }
  // En consola:
    // 0
    // 1
    // 2
    // ...
    // 9
  
  ```
____

- [Volver al indice](../Ejercicios.md)
