
# Exercice site Laure Dinateur version mobile

## Objectifs

* Créer le site internet de la graphiste *Laure Dinateu*r en se basant sur les
  maquettes, images, textes et instructions fournis par le designer.
* Ce site se divise en **3 pages** :
  * `index.html` page d'accueil du site présentant une galerie de 5
    réalisations de Laure Dinateur
  * `informations.html` présentation Laure Dinateur en 3 paragraphes
  * `contact.html` Paragraphes d'informations générales et liste des
    différents moyens de contact.
* Le code CSS du site doit être contenu dans une **feuille de style externe** `main.
  css`. Ce fichier n'existe pas, vous devrez le créer et le lier à vos pages HTML.
* Le code HTML et CSS doit **respecter les standards du W3C** et **doit être validé**
  sur le site https://validator.w3.org/

## Documents utiles

Vous trouverez tous les fichiers utiles à la réalisation du site dans le dossier `_sources/` de ce projet.

Liste des fichiers :
* `images/` ce dossier contient les réalisations, photos et logos et icônes du
  site.
* `maquettes/` les maquettes du site.
* `base.html` fichier HTML de base à copier pour créer vos pages
  HTML.
* `lauredi-contenus.txt` les textes du site.
* `palette.pdf`, `palette.png`, `palette.url` la palette des couleurs du site
  dans différents formats.

## Structure générale du site

Aspect général :
* Couleur d'arrière-plan : `#fdfffc`
* Couleur du texte `#011627`
* Tailles du texte `100%`
* Hauteur de ligne `1.4`
* Police du texte Open Sans`, épaisseur 400 -
  https://fonts.google.com/specimen/Open+Sans
* Police des titres `Changa One`, épaisseur 400 -
  https://fonts.google.com/specimen/Changa+One
* Tailles des titre de niveau 1 `2rem`
* Tailles des titre de niveau 2 `1.5rem`
* Hauteur de ligne des paragraphes `1.5`
* Les liens du site sont rouges `#e71d36` et ne sont **pas soulignés**

Le site se divise en trois parties :
* Entête
* Contenu principal
* Pied de page

### Entête `<header>`
L'entête se compose d'un **logo texte** et d'un **menu de navigation**

Les contenus, textes, de l'entête sont centrés horizontalement.

#### Logo texte
* Lorsqu'on clique sur le logo, cela nous renvoie à la page d'accueil `index.
  html`
* La taille du texte "Laure Dinateur" est de `1.75rem`.

#### Menu de navigation

* Le menu de navigation `<nav>` contient une **liste `<ul>` de trois liens**.
  Mais sur mobile, seuls deux sont visibles,
  car il n'y a pas assez de place en largeur sur les petits terminaux.
* Liste des liens du menu :
  * **Accueil** `index.html` - caché en CSS `display:none;`
  * **Qui suis-je ?** `informations.html`
  * **Me contacter** `contact.html`
* Les éléments de la liste du menu `<li>` s'affichent **sans puces, sans marge
  intérieure et en ligne** `display:inline-block;`
* Pour faciliter la sélection des liens sur mobile, les liens sont espacés de
  `30px.
* La couleur du texte des liens devient bleue `#2ec4b6` lorsqu'ils sont
  survolés `:hover`.

### Contenu principal `<main>`
Contiens le titre principal de la page et ses contenus (images, paragraphes,
titres, sections, liens, éléments importants, figures avec légende)

* Le contenu principal à une marge extérieure gauche et droite de 5%.

### Pied de page `<footer>`
Contiens la **liste des réseaux sociaux** de Laure Dinateur et le **copyright**.
* Les contenus du pied de page sont centrés horizontalement.
* La liste des réseaux sociaux est un élément de navigation `<nav>`, tout
  comme le menu de navigation de l'entête.
* Les images ont une largeur de `50px` sont espacées de `30px`.
* Un filtre gris CSS est appliqué aux images du pied de page `filter: grayscale
  (1);`
* Lorsqu'on passe au-dessus des images avec la souris `:hover`, les images
  reprennent des couleurs `filter: grayscale(0);` avec une transition
  `transition: filter 500ms linear;`

## Travail #1 - Réaliser la page _Qui suis-je ?_

La page de présentation _Qui suis-je ?_ `informations.html` est la plus
simple du site, elle se compose de :
* une image
* un titre principal
* trois paragraphes
* un lien vers le Twitter de Laure Dinateur https://twitter.com/lauredi

Vous devez créer cette page en vous basant sur les instructions de la
_Structure générale du site_ et des différents contenus : textes, palettes,
maquettes, images, ....



### Maquette
![Maquette de la page Me contacter](_sources/maquettes/présentation.png)

### Instructions du designer
* Utiliser les bordures arrondies CSS `border-radius` pour donner la forme de
  cercle à l'image.


