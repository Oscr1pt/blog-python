---
title: "Primeros Pasos"
description: "Aprende a instalar Python y ejecutar tu primer programa usando VS Code o PyCharm."
summary: ""
date: 2023-09-07T16:04:48+02:00
lastmod: 2023-09-07T16:04:48+02:00
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

## Instalar Python

La forma más sencilla de instalar Python en Windows y Mac es descargar el instalador desde el sitio web oficial de Python. Más adelante en esta lección, también veremos cómo ejecutar Python en Linux.

Ir a [python.org](https://www.python.org/) y pase el cursor sobre "Descargas". Aparecerá un cuadro modal que muestra la versión actual de Python para su sistema operativo.

### Instalar Python en macOs

- Haga clic en el botón que muestra la versión actual de Python (del modal anterior) y comenzará a descargar una .pkgarchivo de instalación automáticamente.
- Una vez que el .pkgEl instalador haya terminado de descargarse, ábralo y luego haga clic en "Continuar" en la ventana que se abre.
- Continúe haciendo clic en el botón "Continuar" hasta llegar a la sección "Tipo de instalación". Allí, haga clic en el botón "Instalar".
- Ingrese su contraseña si es necesario, luego inicie la instalación.
- Después de eso, debería recibir un mensaje de felicitación diciendo que Python se ha instalado exitosamente.

Puede verificar la instalación abriendo su terminal y ejecutando:

` python --version o python3 --version.`

También puedes abrir el intérprete de Python ejecutando python o python3en la terminal.

Una terminal es una interfaz de texto que te permite interactuar con tu ordenador escribiendo comandos. Cada sistema operativo incluye una aplicación de terminal predeterminada. En macOS, puedes usar la aplicación Terminal. En Windows, puedes usar el Símbolo del sistema o PowerShell. En Linux, cada entorno de escritorio tiene su propia aplicación de terminal predeterminada, como GNOME Terminal o Konsole.

Tenga en cuenta que, en algunos sistemas macOS y Linux más antiguos, pythonse puede reservar para Python 2, mientras que python3es específicamente para Python 3. Si ejecuta python --versiony ver una versión de Python 2 como Python 2.7.18, entonces es posible que su sistema operativo dependa de algún software escrito en la versión anterior de Python. En ese caso, debería usar python3 para ejecutar su código Python en adelante. Python 2 está en desuso y no debe usarse para ningún desarrollo nuevo.

### Instalar Python en windows

- [python.org](https://www.python.org/) y pasa el cursor sobre "Descargas". Deberías ver una ventana emergente con el mensaje "Descargar para Windows" y un botón de descarga con la versión actual de Python.
- Haga clic en el número de versión y comenzará a descargar un ejecutable de Windows ( .exe) archivo automáticamente.
- Una vez que haya terminado de descargar el instalador de Python para Windows, haga doble clic en él y siga las instrucciones.
- Cuando veas la opción Add python.exe to Path, marque esa opción y luego haga clic en Install NowHacer eso te facilitará las cosas más adelante.

Puede verificar la instalación abriendo un shell de línea de comandos como PowerShell y ejecutando `python --version` También puedes abrir el intérprete de Python ejecutando python.

### Instalar Python en Linux

Para Python en Linux, la mayoría de las distribuciones principales como Ubuntu, Debian y Fedora vienen con Python.

Simplemente abra una terminal y ejecute python --version, o python3 --version:

Si ninguno de los comandos muestra una versión de Python, puede buscar un paquete de instalación para su versión de Linux en https://www.python.org, o busque en línea la forma recomendada de instalar Python para su distribución

## Correr Python de forma local

Después de instalar Python, puedes escribir y ejecutar tus programas usando un editor de código.
A continuación, veremos dos opciones populares.

---

### Opción 1: PyCharm

PyCharm es un entorno de desarrollo diseñado específicamente para trabajar con Python.

1. Abre PyCharm y crea un **New Project**.
2. Crea un archivo llamado `main.py`.
3. Escribe el siguiente código:

```python
print("Hola, mundo")
```

### Opción 2: VS Code

Visual Studio Code es un editor ligero y muy popular.

1. Abre VS Code.
2. Instala la extensión oficial de Python (si aún no la tienes).
3. Crea un archivo llamado main.py.
4. Escribe:

```python
print("Hola, mundo")
```

5. Ejecuta el archivo desde: El botón Run, o La terminal integrada. Si todo esta correcto veras un Hola, mundo.

Si eres principiante absoluto, PyCharm puede resultar más guiado y estructurado.
Si prefieres un editor más ligero y flexible, VS Code es una excelente opción.
Lo importante no es el editor, sino comprender cómo funciona la ejecución de un archivo Python.
