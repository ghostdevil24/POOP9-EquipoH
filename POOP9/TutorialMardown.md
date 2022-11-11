---
marp: true
author: Alejandro García González
size: 4:3
theme: gaia
---
# Tutorial sintaxis markdown #
![Red neuronal width:600px heigth:300 px](https://geekytheory.com/content/images/size/w2000/2014/03/markdown.png)

---
- Elementos de bloque
#### Párrafos y saltos de línea ####

>Para generar un nuevo párrafo en Markdown simplemente separa el texto mediante una línea en blanco (pulsando dos veces intro)
---
#### Encabezados ####
Las # almohadillas son uno de los métodos utilizados en Markdown para crear encabezados. Se usan añadiendo uno por cada nivel.

Ej: 
  - # Encabezado 1
  - ## Encabezado 2
---
#### Citas ####
Las citas se generan utilizando el carácter mayor que > al comienzo del bloque de texto.
Ej : 

> Un país, una civilización se puede juzgar por la forma en que trata a sus animales.  — Mahatma Gandhi
---
#### Listas ####
Para crear listas desordenadas utiliza * asteriscos, - guiones, o + símbolo de suma.

- Elemento de lista 1
- Elemento de lista 2
* Elemento de lista 3
* Elemento de lista 4
+ Elemento de lista 5
+ Elemento de lista 6
---
#### Listas ordenadas ####
Para crear listas ordenadas se utiliza la sintaxis de tipo: «número.» 1.. Al igual que ocurre con las listas desordenadas, también se puede añadir o combinarlas.

1. Elemento de lista 1
2.  Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
        1. Elemento de lista 5
        2. Elemento de lista 6
---
#### Código ####
Se necesitará añadir pequeñas secciones donde mostrar código de otro lenguaje, atajos de teclado, o demás contenido que no debería ser tratado como tal.

Código puro <code>
La forma más sencilla de escribir código en Markdown es envolver el texto entre dos comillas sencillas `. Esto se corresponde con la etiqueta HTML <code>

`Esto es una línea de código`

---
#### Texto preformateado <pre> ####

La otra manera de añadir código en Markdown es comenzar el párrafo con cuatro espacios en blanco. Esto se corresponde con la etiqueta HTML <pre>

    Esto es una línea de código
---
#### Imagenes ####
Para esto, necesitamos escribir en nuestro documento, siendo la sintaxis general la siguiente:

![texto_alternativo](ubicacion_de_la_imagen){width=width height=height}

---
#### Tipo de marcado ####
- Negritas
Sintaxis ** palabra ** donde ** (sin espacios)
**negritas**
- Italica
Sintaxis * palabra * donde * (sin espacios)
*italica*
- Tachado
Sintaxis ~~ donde ~~ (sin espacios)
~~tachado~~


