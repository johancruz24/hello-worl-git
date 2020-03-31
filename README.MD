# Versión del curso.
Versión actual: v1.2.2

# Cabecera H2
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# underlines
Underline 1
-----------
Underline 2
===========

# formatos enphasis
- formato *italica* de la primer forma.
- formatoformato** _italica_ de la segunda forma.
- formato **bold o strong** de la primera forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal. 
- aqui podemos usar *formato italico*, pero tambien **bold**

# listas
1. Esto es un item de listas ordenadas.
2. Esto es un item de listas ordenadas.
3. Esto es un item de listas ordenadas.

-  Esto es un item de listas desordenadas.
-  Esto es un item de listas desordenadas.
-  Esto es un item de listas desordenadas.

# Links
- <a href ="http://www.google.com.co"> Esto es un link en Html</a>
- [Esto es un link en markdown](http://www.google.com.co)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

# Code Snippets
Codigo en JSON
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

Codigo en Javascript
```Javascript
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
JSON / JSON with Comments
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
# Tablas

| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Johan  | Cruz     | 109       |
| Sebas  | Sasnchez | 1098      |
|

# Citas

Esto es un texto referente a una cita que pondremos debajo:

> Esto es una cita

Esto es otro texto que no relaciona la cita anterior.

> Esto es otra cita

# Lineas Horizontales.

Esto es un texto que sera dividido guiones medios.

---
Esto es otro tecto dividido por asteriscos.

***
Dividido por guiones bajos.
___

# Saltos de linea.
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- Lista


