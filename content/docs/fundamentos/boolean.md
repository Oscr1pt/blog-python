---
title: "Boolean y Condicionales"
description: "Learn how to design concise, comprehensive reference pages that document concepts, options, and behavior clearly so users can quickly find exact answers."
summary: ""
date: 2023-10-08T16:13:18+02:00
lastmod: 2023-10-08T16:13:18+02:00
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

## ¿Qué es un valor Booleano?

En Python, un **booleano** (`bool`) es un tipo de dato que solo puede tener dos valores:

- `True` → Verdadero
- `False` → Falso

Los valores booleanos se utilizan principalmente para **evaluar condiciones** dentro de un programa.

### Ejemplo

```python
es_mayor = True
tiene_permiso = False
```

### Expresiones Booleanas

Una expresión booleana es una comparación entre valores que produce como resultado True o False. Ejemplo:

```python
print(5 > 3)
print(10 == 10)
print(7 < 2)
```

Resultado:

True
True
False

## Operadores de Comparación

Los operadores de comparación permiten comparar valores y generar resultados booleanos.

| Operador | Significado | Ejemplo |
|----------|-------------|---------|
| `==` | Igual a | `5 == 5` |
| `!=` | Diferente de | `5 != 3` |
| `>` | Mayor que | `8 > 4` |
| `<` | Menor que | `2 < 7` |
| `>=` | Mayor o igual que | `10 >= 5` |
| `<=` | Menor o igual que | `3 <= 6` |

## Condicionales

Las estructuras condicionales permiten ejecutar diferentes bloques de código dependiendo de si una condición es verdadera o falsa.

Estructura básica

```python
if condicion:
    # código a ejecutar
```

### Condicional con else

El bloque else se ejecuta cuando la condición del if es falsa.

```python
edad = 18

if edad >= 18:
    print("Eres mayor de edad")
else:
    print("Eres menor de edad")
```

### Condicional con elif

elif permite evaluar múltiples condiciones.

```python
nota = 85

if nota >= 90:
    print("Excelente")
elif nota >= 70:
    print("Aprobado")
else:
    print("Reprobado")
```

## Operadores Lógicos

Permiten combinar varias condiciones.

| Operador | Significado |
|----------|-------------|
| and | Ambas condiciones deben ser verdaderas |
| or | Al menos una condición debe ser verdadera |
| not | Niega una condición |

**Ejemplo:**

```python
edad = 20
tiene_id = True

if edad >= 18 and tiene_id:
    print("Puede ingresar")
```

Los valores booleanos y las estructuras condicionales permiten que los programas tomen decisiones. Gracias a ellos, el código puede reaccionar de manera diferente dependiendo de los datos o situaciones que se presenten.
