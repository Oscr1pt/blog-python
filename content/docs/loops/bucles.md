---
title: "Bucles en Python"
description: "Learn how to structure clear, task-focused guides that walk users through real workflows step by step, improving documentation usability and success."
summary: ""
date: 2023-08-07T16:04:48+02:00
lastmod: 2023-08-07T16:04:48+02:00
draft: false
weight: 200
toc: true
params:
  math: false # enable mathematical rendering
  seo:
    title: "" # custom title (optional)
    description: "" # custom description (recommended)
    canonical: "" # custom canonical URL (optional)
    robots: "" # custom robot tags (optional)
---

## ¿Qué es un bucle?

Un **bucle** (loop) es una estructura de control que permite ejecutar un bloque de código varias veces mientras se cumpla una condición o mientras existan elementos por recorrer.

Los bucles son muy útiles para trabajar con secuencias como listas, strings o rangos de números.

En Python existen principalmente dos tipos de bucles:

- `for`
- `while`

---

## Bucle for

El bucle **for** se utiliza para recorrer los elementos de una secuencia, como listas, strings o rangos de números.

### Estructura básica

```python
#Ejemplo con una lista
for elemento in secuencia:
    frutas = ["manzana", "banana", "naranja"]

for fruta in frutas:
    print(fruta)
```

En este ejemplo, el bucle recorre cada elemento de la lista y lo imprime.

### Bucle for con range()

La función **range()** genera una secuencia de números que se utiliza frecuentemente con el bucle for.

**Ejemplo:**

```python
for numero in range(5):
    print(numero)

#Este código imprimirá los números del 0 al 4.

#También se puede definir un rango con inicio y fin:

for numero in range(1, 6):
    print(numero)
```

## Bucle while

El bucle **while** ejecuta un bloque de código mientras una condición sea verdadera.

**Estructura básica:**

while condicion:
    # código a ejecutar

**Ejemplo:**

```python
contador = 0

while contador < 5:
    print(contador)
    contador += 1
```

En este ejemplo, el bucle se ejecutará mientras contador sea menor que 5.

### Diferencia entre for y while

| Bucle | Uso Principal |
|----------|-------------|
| for | Recorrer elementos de una secuencia |
| while | Ejecutar código mientras se cumpla una condición |

Los bucles permiten repetir instrucciones de forma automática, lo que facilita trabajar con colecciones de datos y realizar tareas repetitivas dentro de un programa. Python ofrece los bucles for y while como herramientas principales para controlar la repetición de código.
