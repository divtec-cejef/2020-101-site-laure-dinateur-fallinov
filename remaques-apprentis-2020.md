* Créer un dossier `images/` ou `img/`
  Pour `favicon.ico` on peut simplement la placer à la racine du site.
* Utiliser une `<ul>` pour organiser les réseaux sociaux.
* Éviter les doubles lignes blanches, vides !
* Marges en % uniquement pour les marges gauche et droite !
* Si balise à l'intérieur pas besoin de créer une ligne vide
* Ajouter CSS du reset CSS :
  `<link href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css" rel="stylesheet" >`
* Attention à l'indentation !
* pas d'espace avant et après le `=` des attributs
* éviter les espaces au début des balises sauf si nécessaire.
* Footer : Créer une liste ul de a contenants des img
* Essayer de grouper les déclarations identiques : `h1, h2, h3`
* Placer `<header>` dans `<body>`
* Pas de majuscule dans les noms de class : `monChien -> mon-chien`
* Placer le contenu principal de votre page dans `<main>`
  `<br>` inutile !
    * Ne jamais utiliser <br> pour créer un espacement vertical !
    * Uniquement pour forcer un retour à la ligne !
* CSS spécifique à une page
    - Créer les groupes pour les règles spécifiques à une page.
    - Ajouter la class `page-xxxx` au `<body>` de chaque page.
* Manque l’icône du site : `favicon.ico`
* Google Fonts
    - Un seul lien vers Google Fonts
    - Injecter les Google Fonts dans `main.css` avec la directive `@import`
* Dans le menu principal, ajouter lien vers `index.php`, cacher le `<li>` avec un `diplay:none;`
* Interdiction d’utiliser la balise `<center>`. Remplacer par une `<div>` et y appliquer `text-align: center` en CSS
* Organiser en bloc de commentaire les différents groupes de règles :
    1. Général
    2. Header
    3. Main
    4. Footer
    5. Page accueil
    6. Page informations
    7. ...
* Pas d'id sauf si c'est pour placer une ancre HTML. Remplacer id par class
* Supprimer `height `et `width`. On modifie la taille d'une image en CSS
* Ajouter un ligne vierge à la fin de tous vos fichiers HTML et CSS
* Un `<p>` doit contenir au minimum une phrase
  pour avoir du sens. Si ce n'est pas le cas on préférera une `<div>`.
* Dans body toujours définir :
    * La couleur de fond du site
    * La police de base : famille, taille, couleur, épaisseur
    * La hauteur de ligne
* Dans `<title>` bien mettre les mots-clés correspondant à la page : `Informations | Laure Dinateur | Graphiste`
* Aérer le code en ajoutant une ligne vierge entre chaque déclaration CSS
* Ajouter le reset CSS `normalize.css` avant `main.css`