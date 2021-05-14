# Version
Version actual: 1.2.2
# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines

Underline 1
-----------

Underline 2
=========

# Formatos de enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **strong (bold)** de la primer forma.
- formato __string (bold)__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- aqui podemos usar formato *italico* pero tmabien se puede usar **bold**
 y ~~tachado~~

# Listas
## Lista ordenada
1. Esto es un item.
2. Esto es un item. 
3. Esto es un item. 
4. Esto es un item.
## Lista desordenada
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada. 
- Esto es un item de lista desordenada. 
- Esto es un item de lista desordenada.
# Links
- <a href="https://www.google.com">Esto es un link con HTML</a>
- [Esto es un link en markdown](https://www.google.com)
- [Esto es un link al index](index.html)
# Imagenes
![Logo github](https://image.flaticon.com/icons/png/512/25/25231.png)
# Code snippets
```JSON
[
    {
        "title": "apples",
        "count": [12000,20000],
        "description": {"text":"...","sesitive":false}
    },
    {
        "title": "oranges",
        "count": [17000,null],
        "description": {"text":"...","sesitive":false}
    }
] 
```
```JavaScript
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
| Maxi | Burgos | 25544|
| Pedro | Perez | 24554|
# Citas 
Esto es un texto referente a una cita que pondremos debajo
> Esto es una cita.

Esto es un nuevo parrafo que no tiene relacion con la cita anterior:
> Esto es otra cita

# Lineas divisorias
Esto es otro texto dividido por guiones

---
Esto es otro texto dividido por asteriscos

***
Esto es otro texto dividido por guiones abajo
___
# Saltos de linea o line breaks
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- lista







