![logo_markdown](/static/logo_markdown.png)
# Guía rápida de Markdown

## Salto de línea
Para forzar un salto de línea, deja dos espacios al final de la línea.
```md
Primera oración.  
Segunda oración.
```

## Salto de párrafo
Dejaremos una línea en blanco entre párrafos.
```md
Primer párrafo.

Segundo párrafo.
```

## Títulos
```md
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6
```

## Negrita y cursiva
```md
Esta **palabra** va en negrita.
Esta *palabra* va en cursiva.
Esta ***palabra*** va en negrita y cursiva.
```

## Listas numeradas (ordenadas)
Podemos escribir siempre 1.; Markdown mostrará la numeración correcta.
```md
1. Primer elemento
1. Segundo elemento
    1. Subsegundo elemento
1. Tercer elemento
```

## Listas desordenadas
Podemos usar tanto guiones como asteriscos (se recomienda consistencia en la decisión).
```md
- Primer elemento
- Segundo elemento
- Tercer elemento
    - Subtercer elemento
- Cuarto elemento
```

## Listas de tareas
No funcionan en todos los procesadores de Markdown.
```md
- [ ] Tarea 1
- [x] Tarea 2 (seleccionada)
- [ ] Tarea 3
``` 

## Citas
```md
> Inicio del texto citado
>> Más texto citado aplicando sangría
```

## Texto código
```md
`print("Hola mundo")`
```

## Bloques de código
Se usará triple acento grave (fenced code blocks).
````text
```md
print("Hola mundo")
```
````

## Enlaces
```md
[Moodle Miquel Nebot](https://miquelnebot.eu)
```

## Imágenes
```md
![Texto alt](/assets/logo_markdown.png)
```

## Tablas
```md
| Encabezado 1 | Encabezado 2 |
|:------------:|:------------:|
| Celda 1      | Celda 2      |

```
Opciones de alineación
- :--- Alinear izda
- :---: Alinear centro
- ---: Alinear dcha.
## Otros
### Texto tachado
```md
~~Texto tachado~~
```

### Línea separación horizontal
```md
---
```

### Comentarios HTML
Los comentarios HTML son ampliamente usados.
```md
<!-- Este comentario no se mostrará -->
```

