# Ohmyfood

Projet 3 du parcours Développeur Web d'OpenClassrooms : Dynamisez un site web avec des animations CSS

OhMyFood est une startup qui souhaite s'imposer sur le marché de la gastronomie. Le site permettra à ses utilisateurs de visionner les menus des restaurants gastronomiques et de réserver une table dans le restaurant. Ils pourront également choisir leurs menus à l'avance pour diminuer le temps d'attente sur place.
Le travail sur ce repo s'estconcentré sur l'intrégration d'une maquette, la réalisation d'animations en CSS et l'utilisation de Sass.

## Responsive:

Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires, leur mise en page est libre.

L’ensemble du site devra être responsive sur mobile, tablette et desktop.
Les pages devront passer la validation W3C en HTML et CSS sans erreurs.
Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.

### Contraintes techniques :

- Respecter les maquettes mobiles et réaliser le site en utilisant une approche Mobile first
- Adapter le site pour les tablettes et le desktop
- Couleur de la charte graphique :
  - Violet : #9356dc
  - Rose : #ff79da
  - Turquoise : #99e2d0
- Police :
  - Shrikhand pour le logo et les titres
  - Roboto pour le texte
- **Pas de framework ou de JavaScript** : uniquement du HTML et CSS (SASS) et le HTML ne doit contenir aucun attribut style
- Le code ne doit contenir aucune erreur ni alerte au validateur W3C
- Le site doit être compatible avec les dernières versions de Chrome, Firefox et Safari

### Fonctionnalités, effets graphiques et animations :

- **Header :** Un bouton de retour à l’accueil qui ne doit apparaître que sur les pages de menu
- **Boutons :** Au clic ou au survol, la couleur de fond doit s’éclaircir et l’ombre portée doit être plus visible
- **Bouton “J’aime” :** En forme de coeur, il doit se remplir progressivement au clic ou survol sur desktop
- **Footer :** Au clic sur “Contact” un renvoi vers une adresse mail est effectué
- **Page d’accueil :** Un “loading spinner” couvrant tout l’écran doit apparaître sur la page d’accueil pendant 1 à 3 secondes (uniquement en CSS)
- **Page de menu :** Les plats doivent apparaître progressivement avec un décalage.Ils pourront soit apparaître un par un, soit par groupe “Entrées”, “Plats” et “Desserts”.
  Une “coche” doit coulisser au clic des plats.
