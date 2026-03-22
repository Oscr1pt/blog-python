---
title: "Métodos"
description: "Learn how to structure clear, task-focused guides that walk users through real workflows step by step, improving documentation usability and success."
summary: ""
date: 2023-08-07T16:04:48+02:00
lastmod: 2023-08-07T16:04:48+02:00
draft: false
weight: 300
toc: true
params:
  math: false # enable mathematical rendering
  seo:
    title: "" # custom title (optional)
    description: "" # custom description (recommended)
    canonical: "" # custom canonical URL (optional)
    robots: "" # custom robot tags (optional)
---

## ¿Qué es un método?

Un **método** es una función que pertenece a una clase y define el comportamiento de sus objetos.

Los métodos permiten que los objetos realicen acciones o procesen información.


### Definir un método

Los métodos se definen dentro de una clase utilizando la palabra clave `def`.

**Ejemplo:**

```python
class Persona:
    def saludar(self):
        print("Hola")
```

En este ejemplo, saludar es un método de la clase Persona que nos devuelve `Hola`.

### El parámetro self

El parámetro **self** es obligatorio en los métodos de una clase y se refiere al objeto que está utilizando el método.

Permite acceder a los atributos y otros métodos de la clase.

**Ejemplo:**

```python
class Persona:
    def __init__(self, nombre):
        self.nombre = nombre

    def saludar(self):
        print("Hola, soy", self.nombre)
```

Al definir **self** nos permite acceder al valor de nombre en el metodo saludar.

### Llamar a un método

Para ejecutar un método, se utiliza el objeto seguido del nombre del método.

**Ejemplo:**

```python
persona1 = Persona("Oscar")
persona1.saludar()
```

### Métodos con parámetros

Los métodos también pueden recibir parámetros adicionales.

**Ejemplo:**

```python
class Persona:
    def saludar(self, mensaje):
        print(mensaje, self.nombre)

persona1 = Persona("Oscar")
persona1.saludar("Hola")

#Esto nos devuelve Hola, Oscar
```

### Métodos que retornan valores

Un método puede devolver un resultado utilizando return.

**Ejemplo:**

```python
class Calculadora:
    def sumar(self, a, b):
        return a + b

calc = Calculadora()
resultado = calc.sumar(5, 3)
print(resultado)
```

Los métodos permiten definir el comportamiento de los objetos dentro de una clase. Gracias a ellos, es posible realizar acciones, procesar datos y construir programas más dinámicos y organizados.

