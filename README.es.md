
[![Website](https://img.shields.io/badge/Moodle-miquelnebot.eu-blue)](https://miquelnebot.eu)
[![License](https://img.shields.io/badge/Licencia-MIT-green)](LICENSE)
[![Descarga MD](https://img.shields.io/badge/Descarga_MD-Español-yellow)](https://raw.githubusercontent.com/miquelnebotaragon/guia_basica_markdown/refs/heads/main/README.es.md)
[![Website](https://img.shields.io/badge/Versión-Català-red)](README.md)

<a href="https://daringfireball.net/projects/markdown/"><img src="./static/Markdown-blue-solid.svg.png" style="height: 20%; width:20%;"/></a>

# 📘 Guía rápida de Markdown

## 📚 Contenidos

1. [Salto de línea](#1-salto-de-línea)  
2. [Párrafos](#2-párrafos)  
3. [Títulos o encabezados](#3-títulos-o-encabezados)  
4. [Negrita y cursiva](#4-negrita-y-cursiva)  
5. [Listas numeradas](#5-listas-numeradas)  
6. [Listas desordenadas](#6-listas-desordenadas)  
7. [Lista de tareas](#7-lista-de-tareas)  
8. [Citas](#8-citas)  
9. [Bloques de código](#9-bloques-de-código)  
10. [Enlaces](#10-enlaces)  
11. [Imágenes](#11-imágenes)  
12. [Creación de tablas](#12-creación-de-tablas)  
    - [Control de alineación de columnas](#121-control-de-alineación-de-columnas)  
13. [Otros elementos](#13-otros-elementos)

## 📌 Sintaxis básica

### 1. Salto de línea

En Markdown, si queremos hacer un salto de línea debemos dejar dos espacios (pulsar dos veces la barra espaciadora) al final de la primera oración.

```markdown
Esta sería una primera línea.
Esta sería una segunda línea.
```

**Ejemplo de salida renderizada:**  
Esta sería una primera línea.  
Esta sería una segunda línea.

### 2. Párrafos

Para separar textos en párrafos diferentes, simplemente dejaremos una línea de separación.

```markdown
Esto sería un primer párrafo que termina aquí.

Esto sería un segundo párrafo un poco más largo y que está claramente diferenciado del anterior como puedes ver en este ejemplo.
```

**Ejemplo de salida renderizada:**  
Esto sería un primer párrafo que termina aquí.  
Esto sería un segundo párrafo un poco más largo y que está claramente diferenciado del anterior como puedes ver en este ejemplo.

### 3. Títulos o encabezados

Los crearemos poniendo el símbolo de almohadilla delante del texto que queremos destacar como título. Podemos llegar hasta 6 niveles (6 almohadillas).

```markdown
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6
```

**Ejemplo de salida renderizada:**

# Título 1

## Título 2

### Título 3

#### Título 4

##### Título 5

###### Título 6

### 4. Negrita y cursiva

Podemos usar tanto asteriscos (*) como guiones bajos (_) para aplicar estos formatos siguiendo esta norma:

```markdown
- 1 asterisco abriendo y cerrando: *Texto en cursiva*
- 1 guion bajo abriendo y cerrando: _Texto en cursiva_
- 2 asteriscos abriendo y cerrando: **Texto en negrita**
- 2 guiones bajos abriendo y cerrando: __Texto en negrita__
- 3 asteriscos abriendo y cerrando: ***Cursiva y negrita***
```

**Ejemplo de salida renderizada:**

*Texto en cursiva*, **Texto en negrita** y ***Cursiva y negrita***

### 5. Listas numeradas

Para construir una lista numerada escribiremos un número seguido de un punto. Podemos escribir siempre el número 1, Markdown ya se encarga de mostrar la numeración correcta.

```markdown
1. Primer elemento de la lista numerada
2. Segundo elemento de la lista numerada
3. Tercer elemento de la lista numerada
   1. Si aplicamos una sangría (tabulador) conseguimos subir de nivel
   1. Seguimos con una lista anidada
      1. Y podríamos seguir subiendo niveles
4. Cuarto elemento de la lista numerada
```

**Ejemplo de salida renderizada:**

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

...

### 6. Listas desordenadas

Con los símbolos asterisco (*), guion medio (-) o más (+) seguidos de un espacio, crearemos listas desordenadas. También, igual que hemos visto antes, se pueden anidar.

```markdown
- Elemento 1 de la lista
  - Sub-elemento 1 de la lista
    - Sub-sub-elemento 1 de la lista
- Elemento 2 de la lista
- Elemento 3 de la lista
```

**Ejemplo de salida renderizada:**

- Equipo 1
  - Alba
  - Carlos
  - Juana
- Equipo 2
  - Mercedes
  - Juan Antonio
  - Carmen
    - Antonia (reserva)
  - Aurora

### 7. Lista de tareas

Para crear una lista con casillas de verificación usaremos guiones seguidos de corchetes. Si está marcada, pondremos una "x" dentro, si no, lo dejamos en blanco.

```markdown
- [x] Opción 1
- [ ] Opción 2
- [ ] Opción 3
```

**Ejemplo de salida renderizada:**

- [x] Lunes  
- [ ] Martes  
- [ ] Miércoles

### 8. Citas

Podemos citar texto usando el símbolo mayor que (>) y anidar citas usando más símbolos seguidos.

```markdown
> Esto sería una cita de texto.
>> Más texto citado pero en un nivel anidado.
```

**Ejemplo de salida renderizada:**

> ***Si caes siete veces, levántate ocho.***
>> Proverbio chino

### 9. Bloques de código

Si escribimos código y queremos que se vea resaltado, usaremos el símbolo de **acento abierto** o **backtick** (`) al inicio y al final.

> 💡 **Nota:**  
> El símbolo que se usa para marcar código en línea es el backtick (`).  
> En un teclado español o catalán, se obtiene pulsando la tecla del **acento abierto (`)** y luego la barra espaciadora.  
> En teclados en inglés (EE.UU.), suele estar a la izquierda del número 1.

```markdown
`print("Mi primera línea de código en Python")`
```

**Ejemplo de salida renderizada:**  
`print("Hello World!")`

Para bloques de código más largos usamos tres backticks seguidos (```) e indicamos el lenguaje: Python, Java, etc.

```python
# Esto sería un bloque de código más largo
a = 10
b = 20

if a > b:
    print("A es mayor")
else:
    print("B es mayor")
```

### 10. Enlaces

Para crear enlaces a páginas web usamos la siguiente estructura: entre corchetes `[ ]` el texto visible y entre paréntesis `( )` la URL.

```markdown
[Texto a mostrar](URL)
```

**Ejemplo de salida renderizada:**  
[Mi página web](https://miquelnebot.eu)

### 11. Imágenes

Para insertar imágenes, la sintaxis es similar a los enlaces pero añadimos un signo de exclamación delante.

```markdown
![texto ALT](ruta/a/la/imagen)
```

**Ejemplo de salida renderizada:**

![Ejemplo de imagen](./static/mike_blue_moodle_preview_rev_1.png)

### 12. Creación de tablas

Las tablas se construyen con al menos tres líneas: una para los títulos, otra para la alineación y el resto para los datos.

```markdown
| Columna1 | Columna2 | Columna3 |
|:--------:|:--------:|:--------:|
| Dato1    | Dato2    | Dato3    |
```

**Ejemplo de salida renderizada:**

| Alumnado | Lunes | Martes | Miércoles | Jueves | Viernes |
|:--------:|:-----:|:------:|:---------:|:------:|:-------:|
| Número   | 37    | 45     | 24        | 15     | 17      |

**Consideraciones:**

- Puedes dejar espacios o no entre el texto y las barras (`|`), funcionará igual.
- No es obligatorio que todas las columnas tengan el mismo ancho, pero ayuda a la legibilidad.

#### 12.1 Control de alineación de columnas

- `:---`  Alineación a la izquierda  
- `:---:` Alineación centrada  
- `---:`  Alineación a la derecha

### 13. Otros elementos

- Dos virgulillas (`~~`) al inicio y al final tachan el texto.

```markdown
~~Texto tachado~~
```

**Ejemplo de salida renderizada:**  
~~Érase una vez dos hombres que...~~

- Con la barra invertida (`\`) podemos escapar caracteres para que no se interpreten como sintaxis.

```markdown
\* Este asterisco no aplicará cursiva \*
```

**Ejemplo de salida renderizada:**  
\* Este asterisco no aplicará cursiva \*

- Tres asteriscos, tres guiones o tres guiones bajos generan una línea divisoria.

```markdown
---

- - -

***

* * *
```

**Ejemplo de salida renderizada:**  
---

- También puedes usar etiquetas HTML simples en línea como `<br>`, `<strong>`, etc.

```markdown
<h1>Este es un encabezado de primer nivel</h1>
<p>Este es un párrafo.</p>
```

**Ejemplo de salida renderizada:**  
<h1>Proyecto final de carrera</h1>  
<p>En este proyecto demostraremos cómo...</p>
