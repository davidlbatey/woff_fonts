# Woff Fonts

Some open source OTF fonts which I've converted to WOFF format for use on websites

Example CSS:

```
@font-face {
  font-family: 'LondrinaShadow';
  font-style: normal;
  font-weight: bold;
  src: local('LondrinaShadow Bold'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Bold.eot?#') format('embedded-opentype'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Bold.woff') format('woff'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Bold.ttf') format('truetype'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Bold.svg#Boton-Bold') format('svg');
}
@font-face {
  font-family: 'LondrinaShadow';
  font-style: normal;
  font-weight: normal;
  src: local('LondrinaShadow Regular'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Regular.eot?#') format('embedded-opentype'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Regular.woff') format('woff'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Regular.ttf') format('truetype'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Regular.svg#Boton-Regular') format('svg');
}
@font-face {
  font-family: 'LondrinaShadow';
  font-style: italic;
  font-weight: bold;
  src: local('LondrinaShadow Bold Italic'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Bold-Italic.eot?#') format('embedded-opentype'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Bold-Italic.woff') format('woff'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Bold-Italic.ttf') format('truetype'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Bold-Italic.svg#Boton-Bold-Italic') format('svg');
}
@font-face {
  font-family: 'LondrinaShadow';
  font-style: italic;
  font-weight: normal;
  src: local('LondrinaShadow Italic'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Italic.eot?#') format('embedded-opentype'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Italic.woff') format('woff'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Italic.ttf') format('truetype'),
    url('../fonts/LondrinaShadow/LondrinaShadow-Italic.svg#Boton-Italic') format('svg');
}

p {
  font-family: 'LondrinaShadow', 'Arial Black', Gadget, sans-serif;
  font-style: italic;
  font-weight: bold;
}
```

Note: Use same family for several styles and weight!

