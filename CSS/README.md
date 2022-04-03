# Herramientas
[Colorhunt](https://colorhunt.co/)
Buen website para paleta de colores
[keyword index](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#index)
CSS Reference

[cssfontstack](https://www.cssfontstack.com/)
CSS font: Web safe fonts.
[Fonts by google](https://fonts.google.com/)

[loremipsumgenerator](https://loremipsum.io/es/)
[generator more specific](http://lorem-ipsum.perbang.dk/)
[flaticon](https://www.flaticon.es/)

Syntax


id: Solo identificar 1 solo.
Class: Puede ser para varios elementos. 

Block Elements comunes:
paragraphs, headers, divisions, lists, forms

Common inline Elements:
spans, images, anchors 

# Position propertly

Relative: añade distancia acorde a donde se encuentra el elemento.

Absolute: Añade un margen al elemento acorde al parents elements.

Fixed: 

Activity


HTML
```html
<body>
<div class ="red">
</div>
  
<div class ="blue">
</div>
  
<div class ="yellow">
</div>
</body>
```
CSS
```css
body {
margin: 0;
}
.red {
  height: 100px;
  width: 100px;
  background-color: red;
  position: absolute;
  left: 200px;
  top: 200px;
}

.blue {
  height: 100px;
  width: 100px;
  background-color: blue;
  position: absolute;
  left: 100px;
  top: 100px;
  
}

.yellow {
  height: 100px;
  width: 100px;
  background-color: yellow;
  position: absolute;
}
```
