# Oh My Food

Projet n°3 du parcours "Développeur d'application JavaScript React d'Open Classrooms".
## Objectifs du projet :

- L'objectif est d'intégrer puis de dynamiser une page web avec des animations CSS.
- Lien pour visualiser le site :*https://md-974.github.io/OhMyFood/*

### Pages à intégrer selon les maquettes

- Page d’accueil
- Pages de menu (x4)

### Animation

**Footer**
- Le footer est identique sur toutes les pages.
- Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

**Header**
- Le header est présent sur toutes les pages.
- Sur la page d’accueil, il contient le logo du site.
- Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil

**Boutons**
- Au survol, 
   la couleur de fond des boutons principaux devra légèrement s’éclaircir. 
   L’ombre portée devra également être plus visible.
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. 
   un bouton "J’aime" en forme de cœur est présent sur la maquette. 
   Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut apparaître au survol au lieu du clic.

**Page d’accueil**
- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,toute proposition est donc la bienvenue tant qu’elle est cohérente avec la chartegraphique du site.

**Pages de menu**
- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”.
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension.

## Technologies

**Autorisés:** HTML / CSS / Sass

**Recommandée:** HTML / Sass

**Interdit:** Javascript / Frameworks CSS / Inline CSS

## Notes

**Polices :**

- Logo & titres: **Shrikhand**
- Texte: **Roboto**

**Couleurs :**

- Primaire: #9356DC
- Secondaire: #FF79DA 
- Tertiaire: #99E2D0 

**Contraintes  techniques:**

- Approche mobile-first
- Maquette desktop : à improviser
- Validation W3C HTML & CSS
-    lien validation CSS: http://jigsaw.w3.org/css-validator/validator$link
- Compatibilité : Dernières versions de Chrome, Firefox & Safari
