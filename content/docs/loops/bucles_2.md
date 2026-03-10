---
title: "Control de Bucles"
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

## ¿Qué es el control de bucles?

El **control de bucles** permite modificar el comportamiento de un bucle durante su ejecución.
Python ofrece varias instrucciones que permiten detener, continuar o manejar el flujo de los bucles.

Las principales instrucciones de control de bucles son:

- `break`
- `continue`
- `pass`

### Instrucción break

La instrucción **break** se utiliza para detener completamente la ejecución de un bucle, incluso si la condición del bucle todavía es verdadera.

**Ejemplo:**

```python
for numero in range(10):
    if numero == 5:
        break
    print(numero)
```

En este ejemplo, el bucle se detiene cuando numero es igual a 5.

### Instrucción continue

La instrucción **continue** se utiliza para saltar una iteración del bucle y continuar con la siguiente.

**Ejemplo:**

```python
for numero in range(5):
    if numero == 2:
        continue
    print(numero)
```

En este caso, cuando numero es 2, el programa omite esa iteración y continúa con la siguiente.

### Instrucción pass

La instrucción **pass** se utiliza como marcador de posición cuando se necesita un bloque de código vacío.

**Ejemplo:**

```python
for numero in range(5):
    if numero == 3:
        pass
    print(numero)
```

Pass no realiza ninguna acción, pero permite que el programa se ejecute sin errores.

## Bucles Anidados

Un bucle anidado es un bucle dentro de otro bucle.

**Ejemplo:**

```python
for i in range(3):
    for j in range(2):
        print(i, j)
```

En este ejemplo, el segundo bucle se ejecuta completamente por cada iteración del primer bucle.

Las instrucciones de control de bucles permiten manejar de forma más precisa el flujo de ejecución dentro de un programa. Gracias a break, continue y pass, es posible modificar cómo se comportan los bucles en diferentes situaciones.
