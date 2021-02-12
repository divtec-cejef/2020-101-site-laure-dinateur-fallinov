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
* Pas de majuscule dans les noms de class et d'id: `monChien -> mon-chien`
* Placer le contenu principal de votre page dans `<main>`
  `<br>` inutile !
  * Ne jamais Futiliser <br> pour créer un espacement vertical !
  * Uniquement pour forcer un retour à la ligne !
* CSS spécifique à une page
  - Créer les groupes pour les règles spécifiques à une page.
  - Ajouter la class `page-xxxx` au `<body>` de chaque page.
* Icône du site
  * Manque l’icône du site : `favicon.ico`
  ```html
    <!-- Icone de base -->
    <link rel="icon" type="image/x-icon" href="favicon.ico" sizes="16x16">
  ```
  * Pour générer tous les formats d'icônes :  https://realfavicongenerator.net/
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

  Exemple :
  ```css
  /************************
  ******** GENERAL ********
  ************************/
  ```
* Pas d'id sauf si c'est pour placer une ancre HTML. Remplacer id par class
* Supprimer `height `et `width`. On modifie la taille d'une image en CSS
* Ajouter un ligne vierge à la fin de tous vos fichiers HTML et CSS
* Un `<p>` doit contenir au minimum une phrase
  pour avoir du sens. Si ce n'est pas le cas on préférera une `<div>`.
* Dans body toujours définir :
  * La couleur de fond du site
  * La police de base : famille, taille, couleur, épaisseur
  * La hauteur de ligne
* Dans la `<nav>` mettre le classes aux `<li>` pas aux `<a>`
* Revoir indentation `CTRL+ALT+L`
* Ajouter un espace entre le sélecteur CSS et l'accolade.
* Ajouter une ligne vierge entre deux blocs de règles CSS.
* Ajouter `main.css` après le reset CSS
* **Pas de majuscules** et **pas de caractères spéciaux** (espaces, accents, ... )
  dans les noms de fichiers HTML, CSS images et autres.
* Changer chemin des images, ne pas utiliser `_sources/`
* Tout mettre dans un `<h1>` et ajouter `<br>` pour retour à la ligne.
* pas de caractères spéciaux (accents, espaces) dans les nom des classes CSS.
* Les liens vers les réseaux sociaux font partie d'une nav composé d'une liste de liens contenant des images.
  Voici ma solution :
```html
<nav>
    <ul>
        <li>
            <a href="https://twitter.com/lauredi">
                <img src="img/twitter-draw.png" alt="Twitter">
            </a>
        </li>
        <li>
            <a href="https://www.facebook.com/laure.dinateur">
                <img src="img/facebook-draw.png" alt="Facebook">
            </a>
        </li>
    </ul>
</nav>
```
* Pour toutes les règles du `<header>`, Précéder chaque sélecteur par  `header `
  * Faux : `.logo {...}`
  * Juste :  `header .logo {...}`
* Il faut travailler l'image de fond des liens des éléments de la liste.
```css
.infcontact li a {
    background-image: url('../images/mail.png');
    background-repeat: no-repeat;
    background-size: 20px 20px;
    background-position: 0 2px;
    padding: 0 0 0 30px;
}
```
* Supprimer tous les caractères y compris les espaces avant `<!DOCTYPE html>`
* Remplacer le nom de l'auteur par le votre.
* Renommer `accueil.html` en `index.html`. Il doit toujours y avoir un
  fichier `index.html` à la racine du site.
* Pour atteindre des images dans les fichiers CSS ne pas oublier qu'il
faut en premier sortir du dossier `images/`.
  `background-image : url("../images/phone.png");`
* Ajouter police générique  
