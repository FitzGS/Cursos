```html
<!DOCTYPE html>
```
Indicara la estructura del doctype del html.

Recurso para abreviaciones y ahorrar tiempo :+1: :
[Emmet.io](https://docs.emmet.io/cheat-sheet/)

Lista de todo los caracteres UTF-8 (estandar encondig):
[UTF-8 List](https://www.fileformat.info/info/charset/UTF-8/list.htm)

Meta: Servira para importar informacion al documento.
[Atributos](https://developer.mozilla.org/es/docs/Web/HTML/Element/meta)

Siempre es mejor utilizar:
 ```html
<em></em>
``` 
en vez de
```html
 <i></i>
 ``` 
 o 
 ```html
 <strong></strong>
 ``` 
 en vez de
 ```html
  <b></b>
  ```
  Para mayor uso de información.
# Hyperlink
Para insertar un hipervinculo se utiliza el anchor tag 
```html
<a href="#" >Link</a>
```
![anchor](anchortag.png "Anchor tag estructura")

# Tables
Estructura correcta para usar las tablas
```html
<table>
    <thead>
        <tr>
        <th>Encabezado 1</th>
        <th>Encabezado 2</th>
        <tr>
    </thead> <!-- Titulos o Encabezados-->
    <tbody> <!--Aqui va la informacion -->
        <tr> <!-- Fila-->
            <td></td><!--Columna-->
        </tr>
    </tbody>
    <tfoot></tfoot> <!-- Pie de pagina -->
</table>
```