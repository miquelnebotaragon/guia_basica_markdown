# 📘 Guía básica de Markdown
[![Website](https://img.shields.io/badge/Aula_virtual-miquelnebot.eu-blue)](https://miquelnebot.eu)
[![License](https://img.shields.io/badge/Licencia-CC_BY--SA_4.0-green)](LICENSE)
[![Descarga MD](https://img.shields.io/badge/Descarga_MD-Español-yellow)](https://raw.githubusercontent.com/miquelnebotaragon/guia_basica_markdown/refs/heads/main/README.md)
<a href="https://www.canva.com/design/DAGvPaf3ncs/6qepaI_Ri1enM0pvBUUo1Q/edit?utm_content=DAGvPaf3ncs&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton"><img src="./static/baner_guia_basica_md_cast.png" style="height: 100%; width:100%;"/></a>

## 📚 Contenidos

1. [Introducción](#introducción)
    1. [¿Qué es Markdown?](#-qué-es-markdown)
    1. [¿Dónde puedo conseguir más información?](#-dónde-puedo-conseguir-más-información)
1. [Sintaxis básica](#-sintaxis-básica)  
    1. [Salt de línia](#1-salto-de-línea)
    1. [Párrafos](#2-párrafos)  
    1. [Títulos o encabezados](#3-títulos-o-encabezados)  
    1. [Negrita y cursiva](#4-negrita-y-cursiva)  
    1. [Listas numeradas](#5-listas-numeradas)  
    1. [Listas desordenadas](#6-listas-desordenadas)  
    1. [Lista de tareas](#7-lista-de-tareas)  
    1. [cita](#8-citas)  
    1. [Blocs de codi](#9-bloques-de-código)  
    1. [Enlaces](#10-enlaces)  
    1. [Imágenes](#11-imágenes)  
    1. [Creación de tablas](#12-creación-de-tablas)  
        1. [Control de alineación de columnas](#121-control-de-alineación-de-columnas)  
    1. [Otros elementos](#13-otros-elementos-de-utilidad)

## Introducción
### ❓ Qué es Markdown

**Markdown** es un **lenguaje de marcado ligero** que permite **dar formato a texto plano**. Su sintaxis es sencilla y utiliza símbolos cotidianos como la almohadilla (**#**), el asterisco (**\***) o las llaves (**[ ]**) para introducir modificaciones en nuestros textos.


### 🔗 ¿Dónde puedo conseguir más información?

* John Gruber, creador de este lenguaje, describió las especificaciones originales en la web [*Daring Fireball*](https://daringfireball.net/projects/markdown/). Sin embargo, cabe destacar que la información que encontramos es incompleta y, en algunas partes, está desactualizada.
* [*Common Mark*](https://commonmark.org/) es, a día de hoy, la referencia principal para **estandarizar Markdown** (proyecto más consistente y formal). Prueba [aquí](https://commonmark.org/help/) el **tour** de 1 minuto sobre Markdown.
* Otro recurso recomendado es la completa y bien organizada guía [*Markdown Guide*](https://www.markdownguide.org/) de [Matt Cone](https://www.mattcone.com/) con licenciamiento [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.ca).

## 📌 Sintaxis básica

### 1. Salto de línea

En Markdown, si queremos dar un salto de línea debemos dejar dos espacios (pulsar dos veces en la barra espaciadora) al final de la primera oración.

```Markdown
Esta sería una primera línea.  
Esta sería una segunda línea.
```

✅ **Ejemplo de salida renderizada:**  
Esta sería una primera línea.  
Esta sería una segunda línea.

⚠️ ¡Nota! En muchos entornos modernos como GitHub o Notion no es necesario hacerlo así (su comportamiento es distinto). Depende del renderizador que incorpora la herramienta.

### 2. Párrafos

Para separar textos en párrafos distintos, simplemente dejaremos una línea de separación en blanco entre ellos.

```Markdown
Esto sería un primer párrafo que finaliza aquí.

Esto sería un segundo párrafo un poco más largo y que está claramente diferenciado del anterior como puedes ver en este ejemplo.
```

✅ **Ejemplo de salida renderizada:**  
Esto sería un primer párrafo que finaliza aquí.  
Esto sería un segundo párrafo algo más largo y que está claramente diferenciado del anterior como puedes ver en este ejemplo.

### 3. Títulos o encabezados

Los construiremos poniendo el símbolo de la almohadilla delante del texto que queremos destacar como título. Podemos llegar hasta 6 niveles (6 almohadillas).

```Markdown
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6
```

✅ **Ejemplo de salida renderizada:**

# Título 1

## Título 2

### Título 3

#### Título 4

##### Título 5

###### Título 6

### 4. Negrita y cursiva

Tanto podemos utilizar los asteriscos (*) como los guiones bajos (_) para invocar estos formatos siguiendo esta norma:  

```Markdown
- 1 asterisco abriendo y cerrando: *Texto en cursiva*
- 1 guion bajo abriendo y cerrando: _Texto en cursiva_
- 2 asteriscos abriendo y cerrando: **Texto en negrita**
- 2 guiones bajos abriendo y cerrando: __Texto en negrita__
- 3 asteríscos abriendo y cerrando: ***Cursiva y negrita***
```

✅ **Ejemplo de salida renderizada:**

*Texto en cursiva*, **Texto en negrita** y ***Cursiva y negrita***

### 5. Listas numeradas

Para construir una lista numerada escribiremos un número seguido de punto. Podemos escribir constantemente simplemente el número 1; Markdown ya se encarga de poner el número que corresponda a la numeración.

```Markdown

1. Primer elemento de la lista numerada
2. Segundo elemento de la lista numerada
3. Tercer elemento de la lista numerada
   1. Si aplicamos sangría (tabulador) conseguiremos subir un nivel
   1. Seguimos con una lista anidada
      1. Y todavía podríamos seguir subiendo niveles
4. Cuarto elemento de la lista numerada
```

✅ **Ejemplo de salida renderizada:**

1. Frutas
   1. Manzana
      1. Fuji
      2. Golden
      3. Granny
      4. Reineta
   2. Plátano
   3. Albaricoque
   4. Sandía
2. Verduras
   1. Acelgas
   2. Col
   3. Zanahorias

### 6. Listas desordenadas

Con los símbolos asterisco (*), guion medio (-) o más (+) seguidos de un espacio crearemos listas desordenadas. También, al igual que hemos visto en las anteriores, podemos anidarlas.

```Markdown

- Elemento 1 de la lista
  - Subelemento 1 de la lista
    - Subsubelemento 1 de la lista
- Elemento 2 de la lista
- Elemento 3 de la lista
```

✅ **Ejemplo de salida renderizada:**

- Equipo 1
  - Alba
  - Carles
  - Joana
- Equipo 2
  - Mercè
  - Joan Toni
  - Carme
    - Antònia (reserva)
  - Aurora
  
### 7. Lista de tareas
⚠️ ¡Nota! Esta característica pertenece a la parte de la sintaxis extendida de MD, también llamada [*Flavor*](https://github.github.com/gfm/).

Para tener una lista con indicadores de verificación utilizaremos, por ejemplo el guion medio seguido de las llaves con una "X" en su interior (en las vacías, un espacio).  

```Markdown

- [x] Opción 1
- [ ] Opción 2
- [ ] Opción 3  
```

✅ **Ejemplo de salida renderizada:**

- [x] Lunes  
- [ ] Martes  
- [ ] Miércoles

### 8. Citas

Podemos citar texto utilizando el símbolo mayor que (>) y anidar citas utilizando más símbolos en el momento de escribir.

```Markdown

> Esto sería una cita de texto.
>> Más texto citado pero en otro nivel.
```

✅ **Ejemplo de salida renderizada:**

> ***Si caes siete veces, levántate ocho.***
>> Proverbio chino

### 9. Bloques de código

Si desarrollamos código y queremos que aparezca destacado utilizaremos el acento abierto o "backtick" (`) para abrir y cerrar.


```Markdown
`print("La meva primera línia de codi amb Python")`
```

✅ **Ejemplo de salida renderizada:**  
`print("Hello World!")`

Si tenemos bloques de código más grandes, podemos utilizar tres backticks (\`) para mostrarlo. Escribiremos a continuación el lenguaje que es: Python, Java...

````Markdown
```Python

# Aquí iría un largo bloque de código, por ejemplo de Python.

```
````

✅ **Ejemplo de salida renderizada:**

```Python
a = 10
b = 20

if a > b:
    print("A es mayor")
else:
    print("B es mayor")
```

### 10. Enlaces

Para crear enlaces a páginas web lo haremos siguiendo la siguiente estructura: Entre llaves ([ ]) la información que se mostrará en pantalla (enlace) y, a continuación entre paréntesis (()) la URL de destino.

```Markdown
[Texto para mostrar en pantalla](URL)
```

✅ **Ejemplo de salida renderizada:**  
[Mi web](https://miquelnebot.eu)

También podemos hacer referencia a enlaces creados previamente de la siguiente forma:  
```Markdown
[Enlace 1][1]
[Enlace 2][2]

[1]: URL para el enlace 1
[2]: URL para el enlace 2
```
✅ **Ejemplo de salida renderizada:**   
[Web][1]  
[GitHub][2]

[1]: https://miquelnebot.eu
[2]: https://github.com/miquelnebotaragon

### 11. Imágenes

Para insertar imágenes lo haremos de forma muy parecida a como lo hemos hecho con los enlaces pero, a diferencia de estos, añadiremos un signo de admiración frente a las llaves (![ ]). En este caso, el texto que aparece entrelas llaves es el texto ALT, es decir, el texto alternativo (no se ve directamente, está pensado para la accesibilidad y el SEO).

```Markdown
![text ALT](ruta de acceso a la imagen)
```

✅ **Ejemplo de salida renderizada:**

![Imagen de ejemplo](./static/mike_blue_moodle_preview_rev_1.png)

### 12. Creación de tablas 
⚠️ ¡Nota! Esta característica pertenece a la parte de la sintaxis extendida de MD, también llamada [*Flavor*](https://github.github.com/gfm/).

Las tablas son otro elemento muy utilizado a la hora de crear recursos y documentación en formato MD. Se construyen utilizando al menos 3 líneas. La primera con los títulos de las columnas, la segunda que nos servirá para controlar la alineación de los elementos en las celdas y, a partir de la tercera, todas las que necesitemos para rellenar nuestra tabla.

```Markdown
| Columna1 | Columna2 | Columna3 | Columna4 | Columna5 |
|:--------:|:--------:|:--------:|:--------:|:--------:|
|   Val1   |   Val2   |   Val3   |   Val4   |   Val5   |
```

✅ **Ejemplo de salida renderizada:**
| Alumnado | Lunes | Martes | Miércoles | Jueves | Viernes |
|:--------:|:-----:|:------:|:---------:|:------:|:-------:|
|Nombre    |37     |45      |24         |15      |17       |

Consideraciones:

- Puedes dejar espacios o no entre el texto y las barras (|), funcionará igual.
- Markdown no requiere que las columnas tengan exactamente el mismo ancho pero ayuda visualmente si lo haces así.

#### 12.1 Control de alineación de columnas

`:---`  Alineación a la izquierda  
`:---:` Alineación centrada  
`---:`  Alineación a la derecha

### 13. Otros elementos de utilidad
- Dos virgulillas (~~) delante y detrás tachan el texto.  

```Markdown  
~~Texto tachado~~
```

✅ **Ejemplo de salida renderizada:**  
~~Había una veces dos hombres que...~~

- Gracias a la contrabarra (\\) podremos "escapar" o inutilizar los símbolos que hay detrás de ellos para evitar que invoquen su función.

```Markdown
\* Este símbolo es un asterisco y de esta manera no convertirá a cursiva el texto
```

✅ **Ejemplo de salida renderizada:**  

Esto NO hará negrita, simplemente mostrará los dos asteriscos: \*\*No será negrita\*\*.

- Tres asteriscos o tres guiones (medios o bajos) para crear líneas de división (con o sin espacios entre los símbolos).

```Markdown
---

- - -

***

* * *
```

✅ **Ejemplo de salida renderizada:**
___

- HTML inline: es necesario saber que se pueden incrustar etiquetas HTML sencillas, como \<br>, \<strong>, etc., en los casos en que la sintaxis de Markdown no llega.

```Markdown

<h1>Esto es un encabezado de primer nivel</h1>
<p>Esto es un párrafo.</p>

```

**Ejemplo de salida renderizada:**
<h1>Proyecto final de carrera</h1>
<p>En este proyecto demostraremos cómo...</p>
