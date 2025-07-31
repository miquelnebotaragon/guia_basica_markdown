[![Website](https://img.shields.io/badge/Moodle-miquelnebot.eu-blue)](https://miquelnebot.eu)
[![License](https://img.shields.io/badge/Licencia-MIT-green)](LICENSE)
[![Descarga MD](https://img.shields.io/badge/Descarga_MD-Español-green)](https://raw.githubusercontent.com/miquelnebotaragon/guia_basica_markdown/refs/heads/main/README.es.md)
[![Website](https://img.shields.io/badge/Versión-Català-red)](README.md)


<a href="https://daringfireball.net/projects/markdown/"><img src="./static/Markdown-blue-solid.svg.png" style="height: 20%; width:20%;"/></a>

# 📘 Guía rápida de Markdown

## 📌 Sintaxis básica

### 1. Salto de línea

En Markdown, si queremos hacer un salto de línea debemos dejar dos espacios (presionar dos veces la barra espaciadora) al final de la oración.

Ejemplo:  
Esta sería una primera línea.  
Esta sería una segunda línea.

### 2. Párrafos

Para separar textos en párrafos diferentes, simplemente dejaremos una línea en blanco entre ellos.

Ejemplo:  
Esto sería un primer párrafo que finaliza aquí.

Esto sería un segundo párrafo un poco más largo y claramente diferenciado del anterior, como puedes ver en este ejemplo.

### 3. Títulos o encabezados

Los crearemos poniendo el símbolo de almohadilla delante del texto que queremos destacar como título. Podemos llegar hasta 6 niveles (6 almohadillas).

Ejemplo:  

\# Título 1  
\## Título 2  
\### Título 3  
\#### Título 4  
\##### Título 5  
\###### Título 6  

### 4. Negrita y cursiva

Podemos usar tanto asteriscos (*) como guiones bajos (_) para invocar estos formatos, siguiendo esta norma:

- 1 asterisco abriendo y cerrando: \*Texto en cursiva\*
- 1 guion bajo abriendo y cerrando: \_Texto en cursiva\_
- 2 asteríscos abriendo y cerrando: \*\*Texto en negrita\*\*
- 2 guiones bajos abriendo y cerrando: \_\_Texto en negrita\_\_
- 3 asteriscos abriendo y cerrando: \*\*\*Cursiva y negrita\*\*\*

Ejemplo: *Texto en cursiva*, **Texto en negrita** y ***Cursiva + negrita***

### 5. Listas numeradas

Para construir una lista numerada escribiremos un número seguido de un punto y espacio. Podemos escribir constantemente el número 1, Markdown se encargará de poner la numeración correcta.

Ejemplo:

1. Primer elemento de la lista numerada

1. Segundo elemento de la lista numerada

1. Tercer elemento de la lista numerada

   1. Si aplicamos una sangría (tabulador) subiremos de nivel

   2. Seguimos con una lista anidada

      1. Y todavía podríamos seguir subiendo niveles

1. Cuarto elemento de la lista numerada

### 6. Listas desordenadas

Con los símbolos asterisco (*), guion medio (-) o más (+) seguidos de un espacio, crearemos listas desordenadas. También, como en las anteriores, podemos anidarlas.

Ejemplo:

- Elemento 1 de la lista

  - Sub-elemento 1 de la lista

    - Sub-sub-elemento 1 de la lista

- Elemento 2 de la lista

- Elemento 3 de la lista

### 7. Lista de tareas

Para tener una lista con indicadores de verificación usaremos, por ejemplo, el guion medio seguido de corchetes con una "X" en su interior (o vacío con espacio).

Ejemplo:  

- [X] Lunes
- [ ] Martes
- [ ] Miércoles  

### 8. Citas

Podemos citar texto usando el símbolo mayor que (>) y anidar citas usando más símbolos al escribir.

Ejemplo:

> Esto sería una cita de texto.
>> Más texto citado pero a un nivel anidado.

### 9. Bloques de código

Si desarrollamos código y queremos que aparezca destacado, usaremos las comillas simples invertidas (`) para abrir y cerrar.

Ejemplo:

`print("Mi primera línea de código en Python")`

Si tenemos bloques de código más grandes, podemos usar 3 virgulillas (~). Escribiremos a continuación el lenguaje: Python, Java...

~~~Python
# Esto sería un bloque de código más grande
a = 10
b = 20

if a > b:
    print("A es mayor")
else:
    print("B es mayor")
~~~

### 10. Enlaces

Para crear enlaces a páginas web lo haremos con la siguiente estructura: Entre corchetes ([ ]) la información que se mostrará en pantalla, y a continuación entre paréntesis (( )) la URL del enlace.

Ejemplo:  
[Mi página web](https://miquelnebot.eu)

### 11. Imágenes

Para insertar imágenes lo haremos de manera muy parecida a los enlaces, pero añadiendo un signo de admiración al principio (![ ]). El texto dentro de los corchetes es el texto ALT (alternativo).

Ejemplo:  
![Imagen de ejemplo](./static/mike_blue_moodle_preview_rev_1.png)

### 12. Creación de tablas

Las tablas son otro elemento muy usado en la sintaxis básica de Markdown. Se construyen con un mínimo de 3 líneas: la primera con los títulos de las columnas, la segunda para controlar la alineación del contenido dentro de las celdas, y a partir de la tercera, todas las filas que necesitemos para llenar la tabla.

Ejemplo:

| Alumndo | Lunes | Martes | Miércoles | Jueves | Viernes |
|:-------:|:-----:|:------:|:--------: |:------:|:-------:|
|Número   |37     |45      |24         |15      |17       |

Consideraciones:

- Puedes dejar espacios o no entre el texto y las barras (|), funcionará igual.

- Markdown no requiere que las columnas tengan el mismo ancho exacto, pero ayuda visualmente si lo haces así.

#### 12.1 Control de alineación de columnas

`:---`  Alineación a la izquierda  
`:---:` Alineación centrada  
`---:`  Alineación a la derecha

### 13. Otros elementos

- Dos virgulillas (~~) delante y detrás tachan el texto.

Ejemplo:  
~~Texto tachado~~

- Gracias a la barra invertida (\) podremos "escapar" o desactivar los símbolos que vengan después para evitar que activen su función.

Ejemplo:  
Esto NO hará negrita, simplemente mostrará los dos asteriscos: \*\*No será negrita\*\*.

- Tres asteriscos (***) o tres guiones bajos (___) crean líneas divisorias.

Ejemplo:   
***

- HTML inline: Se pueden incrustar etiquetas HTML simples como `<br>`, `<strong>`, etc., en casos donde Markdown no lo permite.
