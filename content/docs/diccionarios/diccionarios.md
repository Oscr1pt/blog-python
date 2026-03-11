---
title: "Diccionarios en Python"
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

## ¿Qué es un diccionario?

En Python, un **diccionario** es una estructura de datos que permite almacenar información en pares de **clave (key)** y **valor (value)**.

A diferencia de las listas, los diccionarios no utilizan índices numéricos para acceder a los elementos, sino **claves únicas** que identifican cada valor.

Los diccionarios se definen utilizando **llaves `{}`**.

---

### Crear un diccionario

Un diccionario se crea colocando pares de clave y valor separados por dos puntos `:`.

**Ejemplo:**

```python
persona = {
    "nombre": "Oscar",
    "edad": 20,
    "ciudad": "Santiago"
}
```

En este ejemplo:

`"nombre"` es la clave y "Oscar" es su valor.

`"edad"` es la clave y 20 es su valor.

`"ciudad"` es la clave y "Santiago" es su valor.

### Acceder a los valores

Para acceder a un valor dentro de un diccionario se utiliza la clave correspondiente entre corchetes.

**Ejemplo:**

```python
persona = {
    "nombre": "Oscar",
    "edad": 20,
    "ciudad": "Santiago"
}

print(persona["nombre"])
```

Este código mostrará el valor asociado a la clave "nombre".

### Modificar valores

Los valores de un diccionario pueden modificarse fácilmente utilizando su clave.

**Ejemplo:**

```python
persona["edad"] = 21

#Después de esta operación, el valor de "edad" cambiará de 20 a 21.
```

### Agregar nuevos elementos

También es posible agregar nuevos pares de clave y valor a un diccionario.

**Ejemplo:**

```python
persona["telefono"] = "809-000-0000"

#Ahora el diccionario contiene un nuevo elemento llamado "telefono".
```

### Métodos comunes de diccionarios

Python ofrece varios métodos útiles para trabajar con diccionarios.

| Método | Descripción |
|----------|-------------|
| keys() | Devuelve todas las claves del diccionario |
| values() | Devuelve todos los valores |
| items() | Devuelve pares de clave y valor |
| get() | Obtiene el valor de una clave |


**Ejemplo:**

```python
print(persona.keys())
print(persona.values())
print(persona.items())
```

Los diccionarios son estructuras de datos muy útiles en Python para organizar información utilizando pares de clave y valor. Gracias a su flexibilidad, permiten almacenar, acceder y modificar datos de manera eficiente.
