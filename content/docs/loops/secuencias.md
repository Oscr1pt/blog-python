---
title: "Introducción a las Secuencias"
description: "Learn how to structure clear, task-focused guides that walk users through real workflows step by step, improving documentation usability and success."
summary: ""
date: 2023-08-07T16:04:48+02:00
lastmod: 2023-08-07T16:04:48+02:00
draft: false
weight: 100
toc: true
params:
  math: false # enable mathematical rendering
  seo:
    title: "" # custom title (optional)
    description: "" # custom description (recommended)
    canonical: "" # custom canonical URL (optional)
    robots: "" # custom robot tags (optional)
---

## ¿Qué son las secuencias?

En Python, una **secuencia** es una colección ordenada de elementos que pueden almacenarse y accederse mediante un índice.

Las secuencias permiten trabajar con múltiples valores dentro de una sola estructura de datos y recorrerlos fácilmente utilizando bucles.

Algunas características de las secuencias son:

- Son **ordenadas** (mantienen el orden de los elementos)
- Son **indexadas** (cada elemento tiene una posición)
- Son **iterables** (pueden recorrerse con bucles como `for`)

---

### Tipos de Secuencias en Python

Python incluye varios tipos de secuencias integradas. Algunas de las más comunes son:

- **Listas (`list`)**
- **Tuplas (`tuple`)**
- **Cadenas de texto (`str`)**
- **Rangos (`range`)**

---

### Listas

Las **listas** son secuencias que permiten almacenar múltiples valores en una sola variable.
Se definen utilizando corchetes `[]`.

Las listas pueden contener diferentes tipos de datos.

**Ejemplo:**

```python
frutas = ["manzana", "banana", "naranja"]
print(frutas)
```


### Tuplas

Las **tuplas** son similares a las listas, pero son inmutables, lo que significa que no pueden modificarse después de ser creadas.

Se definen utilizando paréntesis ().

**Ejemplo:**

```python
coordenadas = (10, 20)
print(coordenadas)
```

### Cadenas de texto

Los **strings** también son considerados secuencias porque están formados por una serie de caracteres.

**Ejemplo:**

```python
texto = "Python"
print(texto[0])
```

En este ejemplo se accede al primer carácter del string.

## Range

La función **range()** genera una secuencia de números, que es muy utilizada en los bucles.

**Ejemplo:**

```python
numeros = range(5)

for numero in numeros:
    print(numero)
```

Este código imprimirá los números del 0 al 4. Al utilizar range python inicia a contar desde el 0 el número que le pasamos como parametro a la función.

## Acceso a elementos por índice

En las secuencias, cada elemento tiene una posición llamada **índice**.
Los índices comienzan desde 0.

**Ejemplo:**

```python
frutas = ["manzana", "banana", "naranja"]

print(frutas[0])
print(frutas[1])
```

## Longitud de una secuencia

Para conocer la cantidad de elementos de una secuencia se utiliza la función **len()**.

**Ejemplo:**

```python
frutas = ["manzana", "banana", "naranja"]

print(len(frutas))
```

Las secuencias son estructuras fundamentales en Python que permiten almacenar y organizar múltiples valores. Gracias a ellas es posible recorrer datos fácilmente utilizando bucles y realizar operaciones sobre colecciones de información.





