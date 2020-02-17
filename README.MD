# Cabecera

# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underline

Underline 1
-------------

Underline 2
============

# Formato de enfasis
- formato *italica* de la primera forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** primera forma.
- formato __bold o strong__ segunda forma.
- formato ~~tachado~~, formato normal.
- aqui podemos usar *formato italico*, pero tambien **bold** y ~~tachado~~

# Listas
1. esto es un item de lista ordenada.
2. esto es un item de lista ordenada.
3. esto es un item de lista ordenada.

- esto es un item de lista desordenada.
- esto es un item de lista desordenada.
- esto es un item de lista desordenada.

# Links
- <a href="hhtp://www.google.com">Google "Link HTML"</a>
- [Esto es un link Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

# Code Snippets
Código en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

Código en JAVASCRIPT
```JAVASCRIPT
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento |
|--------|----------|-----------|
| Arturo | Rivera | 1028727341 |
|Carolina | Pedroza | 52243346 |

# Citas
Esto es un texto referente a una cita que podremos debajo:
 > Esto es una cita

Esto es un otro texto que no relaciona con la cita anterior:
> Esto es otra cita

# Linea Divisoras
Esto es un texto que sera dividido guines medios.

---
Esto es otro texto dividido por asteriscos.

***
Esto es otro texto dividido por guiones bajos.

___

# Saltos de Líneas
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- Lista