# Coder en html
## Balises obligatoires
```html
<!doctype html>
<html>
  <head>
    <title></title>
  </head>
  <body>
    <p></p>
  </body>  
</html >
```
## Balise meta
```html
<head>
  <meta charset="utf-8">
</head>
```
## Titre de paragraphe
```html
< h1>< /h1>
< h2>< /h2>
< h3>< /h3>
< h4>< /h4>
< h5>< /h5>
< h6>< /h6>
```
## Style texte
```html
< strong>< /strong>
< em>< /em>
```
# Coder en CSS
## Changer le fond
body {
  background: lightblue url("img_tree.gif") no-repeat fixed center;
}
## Changer la couleur du fond
body {background-color: coral;}
## Créer une bordure
h1 {
  border: 5px solid red;
}

h2 {
  border: 4px dotted blue;
}

div {
  border: double;
}
## Changer la couleur de la bordure
div {border-color: coral;}
## Les couleurs en CSS
body {
  color: red;
}

h1 {
  color: #00ff00;
}

p.ex {
  color: rgb(0,0,255);
}
## Changer la fonte de l'écriture
p.a {
  font: 15px Arial, sans-serif;
}

p.b {
  font: italic small-caps bold 12px/30px Georgia, serif;
}
