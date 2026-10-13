# Factorial - Comparación de rendimiento

Este proyecto implementa el cálculo del factorial de un número utilizando dos métodos diferentes:

- Método recursivo
- Método iterativo

El objetivo principal es comparar ambos enfoques y observar su comportamiento y tiempo de ejecución.

## ¿Qué hace el programa?

El programa recibe un número entero y calcula su factorial de dos maneras.

Por ejemplo:

5! = 5 × 4 × 3 × 2 × 1 = 120

Primero se calcula utilizando una función recursiva y después mediante una función iterativa.

Además, el programa mide el tiempo de ejecución de cada método para poder comparar su rendimiento.

## Archivos del proyecto

### `factorial_functions.h`

Contiene la declaración de las funciones utilizadas para calcular el factorial.

### `factorial_functions.cxx`

Contiene la implementación de los dos métodos:

- `factorial_recursive()`
- `factorial_iterative()`

La función recursiva se llama a sí misma hasta llegar al caso base.

La función iterativa utiliza un ciclo para realizar las multiplicaciones.

### `test_factorial.cxx`

Es el programa principal.

Se encarga de:

- Leer el número ingresado.
- Ejecutar el factorial recursivo.
- Ejecutar el factorial iterativo.
- Medir los tiempos de ejecución.
- Mostrar los resultados obtenidos.

### `factorial_table.txt`

Contiene resultados obtenidos al ejecutar el programa con distintos valores.

Permite observar y comparar los resultados y tiempos de ejecución.

### `my_test_factorial.exe`

Es el ejecutable generado a partir del código fuente.

## Ejemplo

Para calcular el factorial de 5:

```bash
my_test_factorial.exe 5
