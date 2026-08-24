# juego-tablero-core

Trabajo para la primera entrega de la materia Diseños y Arquitecturas de Despliegues I. Es el núcleo básico de un juego de tablero hecho en JavaScript para correr con Node.js.

Genera una grilla de 10x10, ubica "casas" en el tablero de forma fija según una semilla (seed) y calcula qué movimientos son válidos desde una posición.


## Integrantes

- Santiago Nicolas Barrionuevo Navarro
- Martín Carvajal
- Maximiliano Torres
- Jose Pepi
- Florencia Moyano


Documentación y Referencias Consultadas
Durante el desarrollo nos apoyamos en la documentación de MDN para la implementación del código:

[Destructuring](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Operators/Destructuring): Usado para extraer directamente las propiedades fila y columna al convertir los números de casilla en coordenadas de la matriz.

[Array.prototype.forEach()](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach): Método utilizado para iterar directamente sobre los elementos del arreglo de casas sin necesidad de armar un bucle for tradicional.

[Operador de Resto (%)](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Operators/Remainder): Usado para calcular la columna exacta dentro de la matriz, devolviendo la posición horizontal.

[Math.floor()](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Math/floor): Aplicado para el redondeo hacia abajo y así obtener la fila exacta de la matriz al convertir el índice.

[Bucle While e Iteración](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Loops_and_iteration): De esta guía tomamos la estructura de control while, la utilización de la propiedad .length para controlar la cantidad requerida de casas y la lógica para evitar bucles infinitos en el generador determinista.
