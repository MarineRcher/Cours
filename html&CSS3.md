Installer extension "live server" pour voir les modifications en direct.

Doctype html
``` html
<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-compatible" content="IE=edge">
  <meta view="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio</title>
  <link rel="stylesheet" href="style.css">
  <script src="script.js"></script>
</head>
<body>


</body>
</html>
```

Un élement html est composé d'une balise d'ouverture et de fermeture :
``` html
<p> contenu </p>
```

Certains éléments n'ont pas de balises fermante :
```html
<hr>
```
Chaque élémnent HTML peut avoir un ou plusieurs attributs :
``` html
<p id="test"> blablabla </p>
<img src="./../..">
```

L'élément '<html>' est la racine de tout le contenu de page web
L'éleement '<bodu>' contient toute la partie visible sur la page web

L'élément head contient des propriétés essentielles pour un site web
``` html
<head></head>
```

Conception page web :

Pour concevoir une page, on doit réfléchir en terme de "conteneur", un contenant qui indique un contenu varié.
Il peut y avoir : texte, images, formulaires, liens, tableaux...

Les contenants servent à créer une structure à la page web. 

### élément div
Un des conteneurs des plus anciens d'HTML. Permet d'effectuer des mises en pages.

### éléments span

Utilisé pour avoir une division dans un paragraphe pour des mises en formes particulières.

### L'élément footer
Permet d'insérer des choses en pied de page. N'implique pas forcément l'usage de <header>

### L'élement nav
Affcihage de barre de naviguation

### main
Indique le contenu principal de la page

### L'élément section
regroupe des éléments d'une page web

###Créer des listes
``` html
Liste à puces
<ul>
    <li></li>
    <li></li>
</ul>

Liste nombre
<ol>
    <li></li>
    <li></li>
</ol>
