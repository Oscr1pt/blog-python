---
title: "Funciones y scope"
description: "Learn how to design concise, comprehensive reference pages that document concepts, options, and behavior clearly so users can quickly find exact answers."
summary: ""
date: 2023-10-07T16:13:18+02:00
lastmod: 2023-10-07T16:13:18+02:00
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
## ¿Qué es una función?

En Python, una **función** es un bloque de código reutilizable que realiza una tarea específica.
Las funciones permiten organizar mejor el código, evitar repeticiones y hacer los programas más fáciles de mantener.

Las funciones se definen utilizando la palabra clave `def`.

**Ejemplo**

```python
def saludar():
    print("Hola, bienvenido a Python")


#Para ejecutar la funcion simplemente se llama por su nombre:
saludar()
```

### Funciones con parámetros

Las funciones pueden recibir parámetros, que son valores que se pasan a la función para que pueda trabajar con ellos.

**Ejemplo:**

```python
def saludar(nombre):
    print("Hola", nombre)

saludar("Pepe")
#Esto devuelve Hola, Oscar
```

En este caso, nombre es un parámetro que recibe el valor "Oscar" cuando se llama la función.

### Funciones que retornan valores

Las funciones también pueden devolver resultados utilizando la palabra clave return. La ventaja de retornar un valor es que luego podemos asignarlo a una variable.

**Ejemplo:**

```python
def sumar(a, b):
    return a + b

resultado = sumar(5, 3)
print(resultado)
```

Aquí la función devuelve la suma de los dos números.

## ¿Qué es el Scope?

El scope (alcance) se refiere al lugar del programa donde una variable puede ser utilizada.

En Python existen principalmente dos tipos de alcance:

- Variable local
- Variable global

### Variables locales

Una variable local es aquella que se define dentro de una función y solo puede usarse dentro de ella.

**Ejemplo**

```python
def mostrar_mensaje():
    mensaje = "Hola desde la función"
    print(mensaje)

mostrar_mensaje()
```

La variable mensaje solo existe dentro de la función.

### Variables globales

Una variable global es aquella que se define fuera de las funciones y puede ser utilizada en diferentes partes del programa.

**Ejemplo:**

```python
nombre = "Oscar"

def saludar():
    print
    he enviado("Hola", nombre)

saludar()
```

La variable nombre puede ser utilizada dentro de la función porque está definida globalmente.

### Palabra clave global

Si se necesita modificar una variable global dentro de una función, se debe utilizar la palabra clave global.

**Ejemplo:**

```python
contador = 0

def aumentar():
    global contador
    contador += 1

aumentar()
print(contador)
```

Las funciones permiten dividir un programa en bloques de código reutilizables y organizados.
El concepto de scope determina dónde pueden utilizarse las variables dentro del programa, lo que ayuda a evitar errores y mejorar la estructura del código.
