---
title: "Sets en Python"
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

## ¿Qué es un set?

En Python, un **set** es una estructura de datos que permite almacenar una colección de elementos **únicos y no ordenados**.

Esto significa que:

- Los elementos **no tienen un orden específico**
- **No se permiten elementos duplicados**

Los sets se definen utilizando **llaves `{}`**, similares a los diccionarios, pero sin pares de clave y valor.

---

### Crear un set

Un set se puede crear colocando los elementos dentro de llaves `{}` separados por comas.

**Ejemplo:**

```python
numeros = {1, 2, 3, 4, 5}
print(numeros)
```

### Sets sin elementos duplicados

Una de las características principales de los sets es que automáticamente eliminan los valores duplicados.

**Ejemplo:**

```python
numeros = {1, 2, 2, 3, 4, 4}
print(numeros)

#En este caso, los valores duplicados se eliminan automáticamente.
```

### Agregar elementos

Para agregar un nuevo elemento a un set se utiliza el método **add()**.

**Ejemplo:**

```python
numeros = {1, 2, 3}
numeros.add(4)

print(numeros)
```

### Eliminar elementos

Para eliminar un elemento de un set se puede utilizar el método remove().

**Ejemplo:**

```python
numeros = {1, 2, 3, 4}
numeros.remove(2)

print(numeros)
```

## Operaciones con sets

Los **sets** permiten realizar varias operaciones matemáticas entre conjuntos.

### Unión

La **unión** combina los elementos de dos sets.

```python
a = {1, 2, 3}
b = {3, 4, 5}

print(a | b)
```

### Intersección

La **intersección** devuelve los elementos que están en ambos sets.

```python
a = {1, 2, 3}
b = {2, 3, 4}

print(a & b)
```

### Diferencia

La **diferencia** devuelve los elementos que están en un set pero no en el otro.

```python
a = {1, 2, 3}
b = {2, 3, 4}

print(a - b)
```

Los sets son estructuras de datos útiles cuando se necesita trabajar con colecciones de elementos únicos. Además, permiten realizar operaciones matemáticas entre conjuntos de manera sencilla y eficiente.
