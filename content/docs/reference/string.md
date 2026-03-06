---
title: "Introduccion a Strings"
description: "Learn how to design concise, comprehensive reference pages that document concepts, options, and behavior clearly so users can quickly find exact answers."
summary: ""
date: 2023-10-10T16:13:18+02:00
lastmod: 2023-10-10T16:13:18+02:00
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

## ¿Qué es un String?

En Python, un string (str) es un tipo de dato utilizado para representar texto.

Los strings se escriben entre comillas simples ' ' o comillas dobles " ".

Ejemplo:
```python
mensaje = "Hola Mundo"
nombre = 'Oscar'
```
### Características de los Strings

- Son inmutables (no pueden modificarse directamente).
- Se pueden almacenar en variables.
- Permiten trabajar con texto dentro de los programas.
- Cada carácter tiene una posición llamada índice.

### Acceso a Caracteres (Indexación)

Cada carácter dentro de un string tiene una posición que comienza desde 0.

```python
texto = "Python"
print(texto[0])  # P
print(texto[1])  # y

#También se pueden usar índices negativos:

print(texto[-1])  # n
```

### Slicing (Rebanado)

Permite extraer una parte del texto.

```python
texto = "Python"
print(texto[0:3])  # Pyt
```

Formato general:

texto[inicio:fin]

## Métodos Comunes de Strings

Python incluye muchos métodos para trabajar con texto.

```python
#Convertir a mayúsculas y minúsculas**

mensaje = "hola"
print(mensaje.upper())  # HOLA
print(mensaje.lower())  # hola


#Eliminar espacios

texto = "  hola  "
print(texto.strip())

#Reemplazar texto

frase = "Hola Mundo"
print(frase.replace("Mundo", "Oscar"))

#Dividir texto

frase = "Hola Mundo Python"
print(frase.split())

#Concatenación
#Unir strings usando el operador +:

nombre = "Oscar"
saludo = "Hola " + nombre
print(saludo)

#f-Strings (Formato moderno)
#Forma más recomendable para combinar texto y variables:

nombre = "Oscar"
edad = 20
print(f"Hola, soy {nombre} y tengo {edad} años")


#Longitud de un String

texto = "Python"
print(len(texto))
```

Los strings son fundamentales en Python, ya que permiten manejar texto, mostrar información al usuario y procesar datos. Comprender cómo manipular cadenas de texto es esencial para desarrollar programas más avanzados.
