EXPLICACIÓN MARKDOWN


# Títulos (# y ##):
\# y \#\# son elementos para definir títulos y subtítulos.
Un # genera un título de nivel 1 (como un encabezado principal).
Dos ## generan un título de nivel 2 (subtítulo).

## Lista títulos
\# Encabezado 1
\#\# Encabezado 2
\#\#\# Encabezado 3
\#\#\#\# Encabezado 4
\#\#\#\#\# Encabezado 5
\#\#\#\#\#\# Encabezado 6

# Listas con viñetas (*):

El asterisco (*) indica que se está creando una lista con viñetas.
Ejemplo del indice de SUMMARY.md:
* [Bienvenido](README.md): Esto es un elemento de lista que contiene un enlace a un archivo llamado README.md. **ABAJO** sigue la explicación de enlaces.

# Enlaces en Markdown indice:
Los enlaces tienen el formato [Texto del enlace](URL o ruta del archivo) :
[Texto]: Es el texto visible en el enlace.
(ruta/archivo.md): Es el archivo o página a la que apunta el enlace.
Ejemplos:
[Introducción](introduccion/README.md): El texto visible será "Introducción", y al hacer clic, llevará al archivo README.md que está en la carpeta introduccion.
[GIT](documentacion/git.md): El texto visible es "GIT", y enlaza al archivo git.md en la carpeta documentacion.

## Enlaces e Imágenes dentro del contenido

Puedes agregar [enlaces](https://www.gitbook.com) e imágenes con el mismo formato.

![Logo de GitBook](https://gitbook-static.s3.amazonaws.com/images/feedback/logo_dark.svg) añadiendo un signo de exclamación **!** al principio.

# Edición de texto

\*Texto en cursiva\* =  *Texto en cursiva* 
\*\*Texto en negrita\*\* = **Texto en negrita**
\*\*\*Texto en cursiva y en negrita\*\*\* = ***Texto en cursiva y negrita***
\`código en línea\` = `código en línea`

# Listas

## Lista no ordenada
- Elemento 1
- Elemento 2
  - Sub-elemento 2.1
  - Sub-elemento 2.2

## Lista ordenada
1. Primer elemento
2. Segundo elemento
   1. Sub-elemento 2.1
   2. Sub-elemento 2.2

# Encabezado

| Encabezado 1 | Encabezado 2 |
| ------------ | ------------ |
| Celda 1      | Celda 2      |
| Celda 3      | Celda 4      |

# Cita

> Esta es una cita. 
El símbolo de mayor (>) se usa para crear citas en bloque. Cualquier texto precedido por > se muestra en un formato de cita.

# Linea divisoria

\-\-\- linea divisoria 
--- 

> **💡 NOTA:**
> Este es un bloque de nota.

> **⚠️ ADVERTENCIA:**
> Esta es una advertencia.

# Código
Aquí hay un ejemplo de código:

```python
print("Hola Mundo")




