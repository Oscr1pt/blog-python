---
title: "Numeros y Operaciones Matematicas"
description: "Learn how to design concise, comprehensive reference pages that document concepts, options, and behavior clearly so users can quickly find exact answers."
summary: ""
date: 2023-10-09T16:13:18+02:00
lastmod: 2023-10-09T16:13:18+02:00
draft: false
weight: 910
toc: true
params:
  seo:
    title: "" # custom title (optional)
    description: "" # custom description (recommended)
    canonical: "" # custom canonical URL (optional)
    robots: "" # custom robot tags (optional)
---

## Números en Python

En Python existen diferentes tipos de datos numéricos que permiten realizar cálculos y operaciones matemáticas dentro de un programa.

Los tipos numéricos más comunes son:

int → números enteros
float → números decimales

**Números Enteros (int)**

Los enteros son números sin parte decimal. Ejemplo:

```python
edad = 20
cantidad = 150
temperatura = -5
```

Los números enteros pueden ser positivos o negativos.

**Números Decimales (float)**

Los números de tipo float representan valores con punto decimal. Ejemplo:

```python
precio = 19.99
altura = 1.75
peso = 68.5
```

## Operadores Matemáticos

Python permite realizar diferentes operaciones matemáticas usando operadores.

| Operación | Operador | Ejemplo |
|-----------|----------|---------|
| Suma | + | 5 + 3 |
| Resta | - | 10 - 4 |
| Multiplicación | * | 6 * 2 |
| División | / | 8 / 2 |
| División entera | // | 9 // 2 |
| Módulo (residuo) | % | 10 % 3 |
| Potencia | ** | 2 ** 3 |

```python
#Ejemplos de Operaciones
a = 10
b = 3

print(a + b)   # suma
print(a - b)   # resta
print(a * b)   # multiplicación
print(a / b)   # división
print(a // b)  # división entera
print(a % b)   # residuo
print(a ** b)  # potencia
```

### Orden de las Operaciones

Python sigue el mismo orden de operaciones que las matemáticas:

Paréntesis ()
Potencias **
Multiplicación y división * / //
Suma y resta + -

```python
#Ejemplo:
resultado = 5 + 2 * 3
print(resultado)

#El resultado será 11, porque primero se realiza la multiplicación.
```

### Funciones Matemáticas Básicas

Python incluye algunas funciones útiles para trabajar con números.

```python
#Valor absoluto
print(abs(-10))
#Redondear números
print(round(4.7))
```

Los números y las operaciones matemáticas son fundamentales en la programación, ya que permiten realizar cálculos, procesar datos y resolver problemas utilizando lógica matemática.
