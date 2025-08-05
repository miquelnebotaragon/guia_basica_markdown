# 📘 Guia bàsica de Markdown
[![Website](https://img.shields.io/badge/Moodle-miquelnebot.eu-blue)](https://miquelnebot.eu)
[![License](https://img.shields.io/badge/Llicència-MIT-green)](LICENSE)
[![Descarga MD](https://img.shields.io/badge/Descarrega_MD-Català-red)](https://raw.githubusercontent.com/miquelnebotaragon/guia_basica_markdown/refs/heads/main/README.md)
[![Website](https://img.shields.io/badge/Versió-Castellà-yellow)](README.es.md)

<a href="https://www.canva.com/design/DAFcJaXg8P8/jVEzvgUu4nwXpsm1tcKJYw/edit?utm_content=DAFcJaXg8P8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton"><img src="./static/baner_guia_basica_md.png" style="height: 100%; width:100%;"/></a>

## 📚 Continguts

1. [Salt de línia](#1-salt-de-línia)  
2. [Paràgrafs](#2-paràgrafs)  
3. [Títols o encapçalaments](#3-títols-o-encapçalaments)  
4. [Negreta i cursiva](#4-negreta-i-cursiva)  
5. [Llistes numerades](#5-llistes-numerades)  
6. [Llistes desordenades](#6-llistes-desordenades)  
7. [Llista de tasques](#7-llista-de-tasques)  
8. [Cites](#8-cites)  
9. [Blocs de codi](#9-blocs-de-codi)  
10. [Enllaços](#10-enllaços)  
11. [Imatges](#11-imatges)  
12. [Creació de taules](#12-creació-de-taules)  
    - [Control d'alineació de columnes](#121-control-dalineació-de-columnes)  
13. [Altres elements](#13-altres-elements)

## 📌 Sintaxi bàsica

### 1. Salt de línia

A Markdown, si volem fer un salt de línia hem de deixar dos espais (prémer dues vegades a la barra espaiadora) al final de la primera oració.

```Markdown
Aquesta seria una primera línia.
Aquesta seria una segona línia.
```

**Exemple de sortida renderitzada:**  
Aquesta seria una primera línia.  
Aquesta seria una segona línia.

### 2. Paràgrafs

Per separar textos en paràgrafs diferents, simplement deixarem una línia de separació.

```Markdown
Això seria un primer paràgraf que finalitza aquí.

Això seria un segon paràgraf una mica més llarg i que està clarament diferenciat de l'anterior com pots veure en aquest exemple.
```

**Exemple de sortida renderitzada:**  
Això seria un primer paràgraf que finalitza aquí.  
Això seria un segon paràgraf una mica més llarg i que està clarament diferenciat de l'anterior com pots veure en aquest exemple.

### 3. Títols o encapçalaments

Els construirem posant el símbol del coixinet al davant del text que volem destacar com a títol. Podem arribar fins a 6 nivells (6 coixinets).

```Markdown
# Títol 1
## Títol 2
### Títol 3
#### Títol 4
##### Títol 5
###### Títol 6
```

**Exemple de sortida renderitzada:**

# Títol 1

## Títol 2

### Títol 3

#### Títol 4

##### Títol 5

###### Títol 6

### 4. Negreta i cursiva

Tant podem emprar els asteriscs (*) com els guions baixos (_) per invocar aquests formats seguint aquesta norma:  

```Markdown
- 1 asterisc obrint i tancant: *Text en cursiva*
- 1 guió baix obrint i tancant: _Text en cursiva_
- 2 asteriscs obrint i tancant: **Text en negreta**
- 2 guions baixos  obrint i tancant: __Text en negreta__
- 3 asteriscs obrint i tancant: ***Cursiva i negreta***
```

**Exemple de sortida renderitzada:**

*Text en cursiva*, **Text en negreta** i ***Cursiva i negreta***

### 5. Llistes numerades

Per construir una llista numerada escriurem un número seguit de punt. Podem escriure constantment simplement el número 1, Markdown ja s'encarrega de posar el nombre que correspon a la numeració.

```Markdown

1. Primer element de la llista numerada
2. Segon element de la llista numerada
3. Tercer element de la llista numerada
   1. Si aplicam un sagnat (tabulador) aconseguirem pujar de nivell
   1. Seguim amb una llista imbricada
      1. I encara més podríem seguir pujant nivells
4. Quart element de la llista numerada
```

**Exemple de sortida renderitzada:**

1. Fruites
   1. Poma
      1. Fuji
      2. Golden
      3. Granny
      4. Reineta
   2. Plàtan
   3. Albercoc
   4. Síndria
2. Verdures
   1. Bledes
   2. Col
   3. Pastanagues

### 6. Llistes desordenades

Amb els símbols asterisc (*), guió mig (-) o més (+) seguits d'un espai crearem llistes desordenades. També, igual que hem vist a les anteriors, podem niar-les.

```Markdown

- Element 1 de la llista
  - Subelement 1 de la llista
    - Subsubelement 1 de la llista
- Element 2 de la llista
- Element 3 de la llista
```

**Exemple de sortida renderitzada:**

- Equip 1
  - Alba
  - Carles
  - Joana
- Equip 2
  - Mercè
  - Joan Toni
  - Carme
    - Antònia (reserva)
  - Aurora
  
### 7. Llista de tasques

Per tenir una llista amb indicadors de verificació farem servir, per exemple el guió mig seguit de les claus amb una "X" al seu interior (a les buides, un espai).  

```Markdown

- [x] Opció 1
- [ ] Opció 2
- [ ] Opció 3  
```

**Exemple de sortida renderitzada:**

- [x] Dilluns  
- [ ] Dimarts  
- [ ] Dimecres

### 8. Cites

Podem citar text fent servir el símbol major què (>) i niar cites fent servir més símbols al moment d'escriure.

```Markdown

> Això seria una cita de text.
>> Més text citat però a un altre nivell.
```

**Exemple de sortida renderitzada:**

> ***Si caus set vegades, aixeca't vuit.***
>> Proverbi xinès

### 9. Blocs de codi

Si desenvolupam codi i volem que aparegui destacat farem servir l'accent obert o "backtick" (`) per obrir i tancar.

> 💡 **Nota:**
> El símbol que cal per marcar codi en línia és el "backtick" (\`).  
> En una distribució de teclat espanyol (ES) o català (CAT), el pots escriure prement la tecla de **l'accent obert (\`)** i tot seguit la **barra espaiadora**.
> Si disposam de distribució de teclat en anglès d'Amèrica, per exemple, el tens al costat esquerre del número 1.


```Markdown
`print("La meva primera línia de codi amb Python")`
```

**Exemple de sortida renderitzada:**  
`print("Hello World!")`

Si tenim blocs de codi més grans, podem emprar tres backticks (\`) per mostrar-lo. Escriurem a continuació el llenguatge que és: Python, Java...

**Exemple de sortida renderitzada:**

```Python
# Això seria un bloc de codi més gran
a = 10
b = 20

if a > b:
    print("A és major")
else:
    print("B és major")
```

### 10. Enllaços

Per crear enllaços a pàgines web ho farem seguint la següent estructura: Entre claus ([ ]) la informació que es mostrarà en pantalla i, a continuació entre parèntesi (()) la URL de l'enllaç.

```Markdown
[Text per mostrar en pantalla](URL)
```

**Exemple de sortida renderitzada:**  
[La meva web](https://miquelnebot.eu)

### 11. Imatges

Per inserir imatges ho farem de manera molt semblant a com ho hem fet amb els enllaços però, a més, afegirem un signe d'admiració al davant de les claus (![ ]). En aquest cas, el text que hi ha a les claus és el text ALT, és a dir, el text alternatiu.

```Markdown
![text ALT](ruta d'accés a la imatge)
```

**Exemple de sortida renderitzada:**

![Imatge d'exemple](./static/mike_blue_moodle_preview_rev_1.png)

### 12. Creació de taules

Les taules són un altre element molt emprat a la sintaxi bàsica de MD. Es construeixen fent servir com a mínim 3 línies. La primera amb els títols de les columnes, la segona que ens servirà per controlar l'alineació dels elements a dins les cel·les i, a partir de la tercera, totes les que necessitem per emplenar la nostra taula.

```Markdown
| Columna1 | Columna2 | Columna3 | Columna4 | Columna5 |
|:--------:|:--------:|:--------:|:--------:|:--------:|
|   Val1   |   Val2   |   Val3   |   Val4   |   Val5   |
```

**Exemple de sortida renderitzada:**
| Alumnat | Dilluns | Dimarts | Dimecres | Dijous | Divendres|
|:-------:|:-------:|:-------:|:--------:|:------:|:--------:|
|Nombre   |37       |45       |24        |15      |17        |

Consideracions:

- Pots deixar espais o no entre el text i les barres (|), funcionarà igual.
- Markdown no requereix que les columnes tinguin exactament el mateix ample, però ajuda visualment si ho fas així.

#### 12.1 Control d'alineació de columnes

`:---`  Alineació a l'esquerra  
`:---:` Alineació centrada  
`---:`  Alineació a la dreta

### 13. Altres elements

- Dues virgulilles (~~) al davant i al darrere tatxen el text.  

```Markdown  
~~Text tatxat~~
```

**Exemple de sortida renderitzada:**  
~~Hi havia una vegades dos homes que...~~

- Gràcies a la contrabarra (\\) podrem "escapar" o inutilitzar els símbols que hi ha al darrere seu per evitar que invoquin la seva funció.

```Markdown
\* Aquest símbol és un asterisc i d'aquesta manera no farà cursiva \*
```

**Exemple de sortida renderitzada:**  

Això NO farà negreta, simplement mostrarà els dos asteriscs: \*\*No serà negreta\*\*.

- Tres asteriscs o tres guions (mitjos o baixos) per crear línies de divisió (amb espais o sense entre els símbols).

```Markdown
---

- - -

***

* * *
```

**Exemple de sortida renderitzada:**
___

- HTML inline: cal saber que es poden incrustar etiquetes HTML senzilles, com \<br>, \<strong>, etc., en casos on Markdown no arriba.

```Markdown

<h1>Això és un encapçalament de primer nivell</h1>
<p>Això és un paràgraf.</p>

```

**Exemple de sortida renderitzada:**
<h1>Projecte final de carrera</h1>
<p>En aquest projecte demostrarem com...</p>
