# PC #1
**course:** Programación Orientada a Objetos I 
**unit:** Unidad 1, 2 y 3 
**cmake project:** poo1_PC1_lab101_v2021_1
## Indicaciones Especificas
- El tiempo límite para la evaluación es 100 minutos.
- Cada pregunta deberá ser respondida en un archivo fuente (`.cpp`) y un archivo cabecera (`.h`) con el número de la pregunta:
    - `p1.cpp, p1.h`
    - `p2.cpp, p2.h`
    - `p3.cpp, p3.h`
- Deberás subir estos archivos directamente a [www.gradescope.com](https://www.gradescope.com) o se puede crear un `.zip` que contenga todos ellos y subirlo.

## Competencias
- Para los alumnos de la carrera de Ciencia de la Computación
    - Aplica conocimientos de computación  apropiados para la solución de problemas definidos y sus requerimientos en la disciplina del programa.(nivel 2)
    - Diseña, implementa y evalúa soluciones a problemas complejos de computación.(nivel 2)
    - Crea, selecciona, adapta y aplica técnicas, recursos y herramientas modernas para la práctica de la computación y comprende sus limitaciones.(nivel 2)

- Para los alumnos de las carreras de Ingeniería
    - Capacidad para aplicar conocimientos de matemática.(nivel 2)
    - Capacidad para diseñar un sistema, un componente o un proceso para satisfacer las necesidades deseadas dentro de restricciones realistas(nivel 2)

## Question #1 - Ecuación Cuadrática (7 points)


Crear un programa que reciba 3 valores del tipo double `(a, b y c)` y que calcule las raíces de una ecuación cuadrática `(ax^2 + bx + c)` y que retorne la raíz de mayor valor, en caso las raíces sean imaginarias el programa retornará "no hay raíces reales".
#### Input Format

```cpp
1
-2
1
```

#### Constraints

```cpp
- El ingreso de los valores no requiere utilizar etiquetas (std::cout)
```

#### Output Format

```cpp
1
```
#### Ejemplo 1
**Input**
```cpp
-1
4
-2
```
**Output**
```cpp
3.41421
```

#### Ejemplo 2
**Input**
```cpp
2
4
3
```
**Output**
```cpp
no hay raíces reales
```

#### Ejemplo 2
**Input**
```cpp
0.5
-1
1
```
**Output**
```cpp
no hay raíces reales
```

## Question #2 - Números triangulares (7 points)

Un número triángulo es aquel número que se obtiene de la suma de los `n` primeros números de naturales, asi por ejemplo 6 es un número triangular formado por la suma de 1 + 2 + 3 ó el número triangular 10 = 1 + 2 + 3 + 4.
Escribir un programa que solicite un `numero` y una función que permita verificar si el número ingresado es triangular o no, el programa debe de retornar si el número es triangular o no.    

#### Input Format

```cpp
630
```

#### Constraints

```cpp
- El ingreso de los valores no requiere utilizar etiquetas (std::cout)
```

#### Output Format

```cpp
triangular
```
#### Ejemplo 1
**Input**
```cpp
500
```
**Output**
```cpp
no triangular
```

#### Ejemplo 2
**Input**
```cpp
406
```
**Output**
```cpp
triangular
```

## Question #3 - Eliminar Vocales (6 points)

Escribir una **función recursiva** cuyo nombre sea `eliminar_vocales` que reciba como parámetro un valor del tipo `std::string` que definirá un **texto** de entrada y a partir del generar un nuevo texto que remueva todas las vocales del texto original, el nuevo texto debera ser devuelto en el valor de retorno de la función.

#### Input Format

```cpp
Este texto tiene vocales
```

#### Constraints

```cpp
- El ingreso de los valores no requiere utilizar etiquetas (std::cout)
```

#### Output Format

```cpp
st txt tn vcls
```
#### Ejemplo 1
**Input**
```cpp
Murcielago
```
**Output**
```cpp
Mrclg
```

#### Ejemplo 2
**Input**
```cpp
Universidad de Ingenieria y Tecnologia - UTEC
```
**Output**
```cpp
nvrsdd d ngnr y Tcnlg - TC
```
