[![Website](https://img.shields.io/badge/Moodle-miquelnebot.eu-blue)](https://miquelnebot.eu)
[![License](https://img.shields.io/badge/Llicència-MIT-green)](LICENSE)

<a href="https://daringfireball.net/projects/markdown/"><img src="./static/Markdown-blue-solid.svg.png" style="height: 20%; width:20%;"/></a>

# 📘 Guia ràpida de Markdown

## 📌 Sintaxi bàsica

### 1. Salt de línia

A Markdown, si volem fer un salt de línia hem de deixar dos espais (prémer dues vegades a la barra espaiadora) al final de l'oració.

Exemple:  
Aquesta seria una primera línia.  
Aquesta seria una segona línia.

### 2. Paràgrafs

Per separar textos en paràgrafs diferents, simplement deixarem una línia de separació.

Exemple:  
Això seria un primer paràgraf que finalitza aquí.  
Això seria un segon paràgraf una mica més llarg i que està clarament diferenciat de l'anterior com pots veure en aquest exemple.

### 3. Títols o encapçalaments

Els construirem posant el símbol del coixinet al davant del text que volem destacar com a títol. Podem arribar fins a 6 nivells (6 coixinets).

Exemple:  
\# Titol 1  
\## Titol 2  
\### Títol 3  
\#### Títol 4  
\##### Títol 5  
\###### Títol 6  

### 4. Negreta i cursiva

Tant podem emprar els asteriscs (*) com els guions baixos (_) per invocar aquests formats seguint aquesta norma:  

- 1 asterisc obrint i tancant: \*Text en cursiva\*
- 1 guió baix obrint i tancant: \_Text en cursiva\_
- 2 asteriscs obrint i tancant: \*\*Text en negreta\*\*
- 2 guions baixos  obrint i tancant: \_\_Text en negreta\_\_
- 3 asteriscs obrint i tancant: \*\*\*Cursiva i negreta\*\*\*

Exemple: *Text en cursiva*, **Text en negreta** i ***Cursiva i negreta***

### 5. Llistes numerades

Per construir una llista numerada escriurem un número seguit de punt. Podem escriure constantment simplement el número 1, Markdown ja s'encarrega de posar el nombre que correspon a la numeració.

Exemple:

1. Primer element de la llista numerada
2. Segon element de la llista numerada
3. Tercer element de la llista numerada
   1. Si aplicam un sagnat (tabulador) aconseguirem pujar de nivell
   1. Seguim amb un llista niada
      1. I encara més podríem seguir pujant nivells
4. Quart element de la llista numerada

### 6. Llistes desordenades

Amb els símbols asterisc (*), guió mig (-) o més (+) seguits d'un espai crearem llistes desordenades. També, igual que hem vist a les anteriors, podem niar-les.

Exemple:

- Element 1 de la llista
  - Subelement 1 de la llista
    - Subsubelement 1 de la llista
- Element 2 de la llista
- Element 3 de la llista

### 7. Llista de tasques

Per tenir una llista amb indicadors de verificació farem servir, per exemple el guió mig seguit de les claus amb una "X" al seu interior (a les buides, un espai).  

Exemple:  

- [X] Dilluns
- [ ] Dimarts
- [ ] Dimecres  

### 8. Cites

Podem citar text fent servir el símbol major què (>) i niar cites fent servir més símbols al moment d'escriure.

Exemple:

> Això seria una cita de text.
>> Més text citat però a un nivell niat.

### 9. Blocs de codi

Si desenvolupam codi i volem que aparegui destacat farem servir les cometes simples (`) per obrir i tancar.

Exemple:

`print("La meva primera línia de codi amb Python")`

Si tenim blocs de codi més grans podem emprar 3 virgulilles (~) per mostrar-lo. Escriurem a continuació el llenguatge que és: Python, Java...

~~~Python
#Això seria un bloc de codi més gran
a = 10
b = 20

if a > b:
    print("A és major")
else:
    print("B és major")
~~~

### 10. Enllaços

Per crear enllaços a pàgines web ho farem seguint la següent estructura: Entre claus ([ ]) la informació que es mostrarà en pantalla i, a continuació entre parèntesi (()) la URL de l'enllaç.

Exemple:  
[La meva web](https://miquelnebot.eu)

### 11. Imatges

Per inserir imatges ho farem de manera molt semblant a com ho hem fet amb els enllaços però, a més, afegirem un signe d'admiració al davant de les claus (![ ]). En aquest cas, el text que hi ha a les claus és el text ALT, és a dir, el text alternatiu.

Exemple:

![Imatge d'exemple](./static/mike_blue_moodle_preview_rev_1.png)

### 12. Creació de taules

Les taules són un altre element molt emprat a la sintaxi bàsica de MD. Es construeixen fent servir com a mínim 3 línies. La primera amb els títols de les columnes, la segona que ens servirà per controlar l'alineació dels elements a dins les cel·les i, a partir de la tercera, totes les que necessitem per emplenar la nostra taula.

Exemple:  
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

Exemple:  
~~Text tatxat~~

- Gràcies a la contrabarra (\\) podrem "escapar" o inutilitzar els símbols que hi ha al darrere seu per evitar que invoquin la seva funció.

Exemple:
Això NO farà negreta, simplement mostrarà els dos asteriscs: \*\*No serà negreta\*\*.

- Tres asteriscs o tres guions baixos per crear línies de divisió.

___

- HTML inline: cal saber que es poden incrustar etiquetes HTML senzilles, com \<br>, \<strong>, etc., en casos on Markdown no arriba.
