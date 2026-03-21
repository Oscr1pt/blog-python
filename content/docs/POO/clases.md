---
title: "Clases y Objetos"
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

## ¿Qué es una clase?

Una **clase** es una plantilla o modelo que define las características (**atributos**) y comportamientos (**métodos**) que tendrán los objetos.

Las clases permiten agrupar datos y funciones relacionadas en una sola estructura.

---

### Crear una clase

En Python, las clases se definen utilizando la palabra clave `class`.

**Ejemplo:**

```python
class Celular():
    marca = "samsung"
    modelo = "S23"
    camara = "48mp"

celular1 = Celular()
print(celular1.marca)

#Esto imprime: samsung
```

En este ejemplo se crea una clase llamada Celular. Creamos unas Claves llamadas marca, modelo y camara con sus valores.

## ¿Qué es un objeto?

Un objeto es una instancia de una clase. Es decir, es una representación concreta creada a partir de una clase.

**Ejemplo:**

```python
persona1 = Persona()
```

Aquí se crea un objeto llamado persona1 basado en la clase Persona.


### Método constructor __init__

El método __init__ es un constructor que se ejecuta automáticamente cuando se crea un objeto.
Se utiliza para inicializar los atributos del objeto.

**Ejemplo:**

```python
class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad
```

### Crear objetos con atributos

Una vez definida la clase, podemos crear objetos pasando los valores necesarios.

**Ejemplo:**

```python
class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad

persona1 = Persona("Oscar", 20)

print(persona1.nombre)
print(persona1.edad)
```

En este caso:

nombre y edad son atributos del objeto
persona1 es una instancia de la clase Persona

### Atributos

Los atributos son variables que pertenecen a un objeto y almacenan información.

Se definen dentro del método __init__ utilizando self.

**Ejemplo:**

```python
class Persona:
    def __init__(self, nombre):
        self.nombre = nombre
```

### Modificar atributos

Los atributos pueden modificarse después de crear el objeto.

**Ejemplo:**

```python
persona1 = Persona("Oscar")
persona1.nombre = "Daniel"

print(persona1.nombre)
```

### Múltiples objetos

Se pueden crear varios objetos a partir de la misma clase.

**Ejemplo:**

```python
persona1 = Persona("Oscar", 20)
persona2 = Persona("Ana", 25)

print(persona1.nombre)
print(persona2.nombre)
```

Cada objeto tiene sus propios valores.

Las clases y objetos son la base de la Programación Orientada a Objetos. Permiten crear estructuras organizadas que representan entidades del mundo real, facilitando la reutilización y el mantenimiento del código.
