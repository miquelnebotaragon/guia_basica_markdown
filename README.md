# 📘 Guia bàsica de Markdown
[![Website](https://img.shields.io/badge/Aula_virtual-miquelnebot.eu-blue)](https://miquelnebot.eu)
[![License](https://img.shields.io/badge/Llicència-CC_BY--SA_4.0-green)](LICENSE)
[![Descarga MD](https://img.shields.io/badge/Descarrega_MD-Català-red)](https://raw.githubusercontent.com/miquelnebotaragon/guia_basica_markdown/refs/heads/main/README.md)
<a href="https://www.canva.com/design/DAGvPaf3ncs/6qepaI_Ri1enM0pvBUUo1Q/edit?utm_content=DAGvPaf3ncs&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton"><img src="./static/baner_guia_basica_md_cat.png" style="height: 100%; width:100%;"/></a>

## 📚 Continguts

1. [Introducció](#introducció)
    1. [Què és Markdown?](#-què-és-markdown)
    1. [On puc aconseguir més informació?](#-on-puc-aconseguir-més-informació)
1. [Sintaxi bàsica](#-sintaxi-bàsica)  
    1. [Salt de línia](#1-salt-de-línia)
    1. [Paràgrafs](#2-paràgrafs)  
    1. [Títols o encapçalaments](#3-títols-o-encapçalaments)  
    1. [Negreta i cursiva](#4-negreta-i-cursiva)  
    1. [Llistes numerades](#5-llistes-numerades)  
    1. [Llistes desordenades](#6-llistes-desordenades)  
    1. [Llista de tasques](#7-llista-de-tasques)  
    1. [Cites](#8-cites)  
    1. [Blocs de codi](#9-blocs-de-codi)  
    1. [Enllaços](#10-enllaços)  
    1. [Imatges](#11-imatges)  
    1. [Creació de taules](#12-creació-de-taules)  
        1. [Control d'alineació de columnes](#121-control-dalineació-de-columnes)  
    1. [Altres elements](#13-altres-elements-dutilitat)

## Introducció
### ❓ Què és Markdown

**Markdown** és un **llenguatge de marcatge lleuger** que permet **donar format a text pla**. La seva sintaxi és senzilla i empra símbols quotidians com el coixinet (**#**), l'asterisc (**\***) o la clau (**[ ]**) per introduir modificacions als nostres textos.


### 🔗 On puc aconseguir més informació?

* John Gruber, creador d'aquest llenguatge, va descriure les especificacions originals al web [*Daring Fireball*](https://daringfireball.net/projects/markdown/). Tot i això, cal destacar que la informació que hi trobam és incompleta i, en algunes parts, està desactualitzada.
* [Common Mark](https://commonmark.org/) és, a dia d'avui, la  referència principal per **estarditzar Markdown** (projecte més consistent i formal). Prova [aquí](https://commonmark.org/help/) el **tour** d'1 minut sobre Markdown.
* Un altre recurs recomanat és la completa i ben organitzada guia [*Markdown Guide*](https://www.markdownguide.org/) de [Matt Cone](https://www.mattcone.com/) amb llicenciament [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.ca).

## 📌 Sintaxi bàsica

### 1. Salt de línia

A Markdown, si volem fer un salt de línia hem de deixar dos espais (prémer dues vegades a la barra espaiadora) al final de la primera oració.

```Markdown
Aquesta seria una primera línia.
Aquesta seria una segona línia.
```

✅ **Exemple de sortida renderitzada:**  
Aquesta seria una primera línia.  
Aquesta seria una segona línia.

⚠️ Nota! En molts entorns moderns com GitHub o Notion no és necessari fer-ho així (el seu comportament és diferent). Depèn del renderitzador que incorpora l'eina.

### 2. Paràgrafs

Per separar textos en paràgrafs diferents, simplement deixarem una línia de separació en blanc entre ells.

```Markdown
Això seria un primer paràgraf que finalitza aquí.

Això seria un segon paràgraf una mica més llarg i que està clarament diferenciat de l'anterior com pots veure en aquest exemple.
```

✅ **Exemple de sortida renderitzada:**  
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

✅ **Exemple de sortida renderitzada:**

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
- 2 guions baixos obrint i tancant: __Text en negreta__
- 3 asteriscs obrint i tancant: ***Cursiva i negreta***
- 3 guions baixos obrint i tancant: ___Cursiva i negreta___
```

✅ **Exemple de sortida renderitzada:**

*Text en cursiva*, **Text en negreta** i ***Cursiva i negreta***

⚠️ Nota! Si estam escrivint per a GitHub, Discord o Notion, millor emprar asterisc (*) per emfatitzar els nostres textos. Generalment són més segurs a l'hora d'utilitzar Markdown.

### 5. Llistes numerades

Per construir una llista numerada escriurem un número seguit de punt. Podem escriure constantment simplement el número u (1), Markdown ja s'encarrega de posar el nombre que correspon a la numeració.

```Markdown
1. Primer element de la llista numerada
2. Segon element de la llista numerada
3. Tercer element de la llista numerada
   1. Si aplicam un sagnat (tabulador) aconseguirem pujar de nivell
   1. Seguim amb una llista imbricada
      1. I encara més podríem seguir pujant nivells
4. Quart element de la llista numerada
```

✅ **Exemple de sortida renderitzada:**

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

✅ **Exemple de sortida renderitzada:**

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
⚠️ Nota! Aquesta característica pertany a la part de la sintaxi extesa de MD, també anomenada [*Flavor*](https://github.github.com/gfm/).

Per tenir una llista amb indicadors de verificació farem servir, per exemple el guió mig seguit de les claus amb una "X" al seu interior (a les buides, un espai).  

```Markdown

- [x] Opció 1
- [ ] Opció 2
- [ ] Opció 3  
```

✅ **Exemple de sortida renderitzada:**

- [x] Dilluns  
- [ ] Dimarts  
- [ ] Dimecres

### 8. Cites

Podem citar text fent servir el símbol major què (>) i niar cites fent servir més símbols al moment d'escriure.

```Markdown

> Això seria una cita de text.
>> Més text citat però a un altre nivell.
```

✅ **Exemple de sortida renderitzada:**

> ***Si caus set vegades, aixeca't vuit.***
>> Proverbi xinès

### 9. Blocs de codi

Si desenvolupam codi i volem que aparegui destacat farem servir l'accent obert o *backtick* (`) per obrir i tancar.


```Markdown
`print("La meva primera línia de codi amb Python")`
```

✅ **Exemple de sortida renderitzada:**  
`print("Hello World!")`

Si tenim blocs de codi més grans, podem emprar tres *backticks* (\`) per mostrar-lo. Escriurem a continuació el llenguatge que és: Python, Java...

````Markdown
```Python

# Aquí aniria un bloc de codi llarg, per exemple de Python.

```
````

✅ **Exemple de sortida renderitzada:**

```Python
a = 10
b = 20

if a > b:
    print("A és major")
else:
    print("B és major")
```

### 10. Enllaços

Per crear enllaços a pàgines web ho farem seguint la següent estructura: Entre claus ([ ]) la informació que es mostrarà en pantalla (enllaç) i, a continuació entre parèntesi (()) la URL de destí.

```Markdown
[Text per mostrar en pantalla](URL)
```

✅ **Exemple de sortida renderitzada:**  
[La meva pàgina web](https://miquelnebot.eu)

També podem fer referència a enllaços creats prèviament de la següent manera:  
```Markdown
[Enllaç 1][1]
[Enllaç 2][2]

[1]: URL per a l'enllaç 1
[2]: URL per a l'enllaç 2
```
✅ **Exemple de sortida renderitzada:**   
[Web][1]  
[GitHub][2]

[1]: https://miquelnebot.eu
[2]: https://github.com/miquelnebotaragon

### 11. Imatges

Per inserir imatges ho farem de manera molt semblant a com ho hem fet amb els enllaços però, a diferència d'aquests, afegirem un signe d'admiració al davant de les claus (![ ]). En aquest cas, el text que hi ha a les claus és el text ALT, és a dir, el text alternatiu (no es veu directament, està pensat per a l'accessibilitat i el SEO). Entre parèntesi, la ruta completa a la imatge.

```Markdown
![text ALT](ruta d'accés a la imatge)
```

✅ **Exemple de sortida renderitzada:**

![Imatge d'exemple](./static/mike_blue_moodle_preview_rev_1.png)

⚠️ ¡Nota! Aquí cal diferenciar que podem fer referència a rutes absolutes (imatges d'Internet https://web.com/imatge.jpg) com a d'altres que tenguem en un repositori propi (rutes relatives). Per exemple, si volem mostrar una imatge d'un directori del nostre repositori de GitHub ho farem de la següent manera: `![text ALT](./static/nombre_imagen.jpg)`

### 12. Creació de taules 
⚠️ Nota! Aquesta característica pertany a la part de la sintaxi extesa de MD, també anomenada [*Flavor*](https://github.github.com/gfm/).

Les taules són un altre recurs molt emprat a l'hora de crear documentació en format MD. Es construeixen fent servir com a mínim 3 línies. La primera amb els títols de les columnes, la segona que ens servirà per controlar l'alineació dels elements a dins les cel·les i, a partir de la tercera, totes les que necessitem per emplenar la nostra taula.

```Markdown
| Columna1 | Columna2 | Columna3 | Columna4 | Columna5 |
|:--------:|:--------:|:--------:|:--------:|:--------:|
|   Val1   |   Val2   |   Val3   |   Val4   |   Val5   |
```

✅ **Exemple de sortida renderitzada:**
| Alumnat | Dilluns | Dimarts | Dimecres | Dijous | Divendres |
|:-------:|:-------:|:-------:|:--------:|:------:|:---------:|
|Nombre   |37       |45       |24        |15      |17         |

Consideracions:

- Pots deixar espais o no entre el text i les barres verticals (|), funcionarà igual.
- Markdown no requereix que les columnes tinguin exactament el mateix ample, però ajuda visualment si ho fas així.

#### 12.1 Control d'alineació de columnes

`:---`  Alineació a l'esquerra  
`:---:` Alineació centrada  
`---:`  Alineació a la dreta

### 13. Altres elements d'utilitat
- Dues virgulilles (~~) al davant i al darrere tatxen el text.  

```Markdown  
~~Text tatxat~~
```

✅ **Exemple de sortida renderitzada:**  
~~Hi havia una vegada dos homes que...~~

- Gràcies a la contrabarra (\\) podrem "escapar" o inutilitzar els símbols que hi ha al darrere seu per evitar que invoquin la seva funció.

```Markdown
\* Aquest símbol és un asterisc i d'aquesta manera no farà cursiva
```

✅ **Exemple de sortida renderitzada:**  

Això NO farà negreta, simplement mostrarà els dos asteriscs: \*\*no serà negreta\*\*.

- Tres asteriscs o tres guions (mitjos o baixos) per crear línies de divisió (amb espais o sense entre els símbols).

```Markdown
---

- - -

***

* * *
```

✅ **Exemple de sortida renderitzada:**
___

- HTML inline: cal saber que es poden incrustar, a determinats entors (alguns altres ho bloquegen per seguretat), etiquetes HTML senzilles, com \<br>, \<strong>, etc., en els casos on la sintaxi de Markdown no arriba.

```Markdown

<h1>Això és un encapçalament de primer nivell</h1>
<p>Això és un paràgraf.</p>

```

**Exemple de sortida renderitzada:**
<h1>Projecte final de carrera</h1>
<p>En aquest projecte demostrarem com...</p>
