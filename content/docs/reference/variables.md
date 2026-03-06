---
title: "Variables y tipos de datos"
description: "Learn how to design concise, comprehensive reference pages that document concepts, options, and behavior clearly so users can quickly find exact answers."
summary: ""
date: 2023-10-11T16:13:18+02:00
lastmod: 2023-10-11T16:13:18+02:00
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

## ¿Qué es una variable?

En Python, una variable es un espacio en memoria que se utiliza para almacenar información.

A diferencia de otros lenguajes, Python no requiere declarar el tipo de dato explícitamente, ya que lo detecta automáticamente. Ejemplo:


```python
nombre = "Oscar"
edad = 20
altura = 1.75
```

En este ejemplo:

nombre almacena texto
edad almacena un número entero
altura almacena un número decimal

### Reglas para nombrar variables

Deben comenzar con una letra o guion bajo (_)

No pueden comenzar con números

No pueden usar palabras reservadas del lenguaje

Son sensibles a mayúsculas y minúsculas (Edad ≠ edad)

## Tipos de Datos en Python

Python maneja varios tipos de datos básicos:

1. Enteros (int)

Representan números sin decimales.

```python
cantidad = 10
```

2. Decimales (float)

Representan números con punto decimal.

```python
precio = 99.99
```

3. Cadenas de texto (str)

Representan texto y se escriben entre comillas.

```python
mensaje = "Hola Mundo"
```

4.  Booleanos (bool)

Representan valores lógicos: Verdadero o Falso.

```python
activo = True
es_mayor = False
```

### Verificar el tipo de una variable

Podemos usar la función type() para conocer el tipo de dato almacenado:

```python
edad = 20
print(type(edad))
```

### Conversión de Tipos (Casting)

Python permite convertir un tipo de dato en otro:

```python
numero = "10"
numero_entero = int(numero)
```

Algunas funciones de conversión comunes:

- int() → convierte a entero
- float() → convierte a decimal
- str() → convierte a texto
- bool() → convierte a booleano
