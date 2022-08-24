# Projet OhMyfood
Troisème projet  du parcours "Développeur web" de **OpenClassrooms**. L'objectif est de dynamisez une page web avec des animations CSS.

## Objectifs
1. Développer un site proposant le menu de 4 grands restaurants parisiens.
2. Permettre la réservation en ligne et la composition de menus.

## Technologies
**Autorisés**: HTML, CCS, SASS   
**Recommandée**: SASS   
**Interdit**: Javascript, Frameworks    

## Compatibilité
La cible étant les personnes connectées et pressées, le site sera développé en utilisant l’approche mobile-first.
Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires, leur mise en page est libre.
- L’ensemble du site devra être responsive sur mobile, tablette et desktop.
- Les pages devront passer la validation W3C en HTML et CSS sans erreur.
- Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.

## Livrables attendus
### Contenu des pages 
#### Page d’accueil (x1)
- Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.
- Une courte présentation de l’entreprise.
- Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.

#### Pages de menu (x4)
- 4 pages contenant chacune le menu d’un restaurant. Footer
- Le footer est identique sur toutes les pages.
- Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

#### Header
- Le header est présent sur toutes les pages.
- Sur la page d’accueil, il contient le logo du site.
- Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil

### Effets graphiques et animations

#### Boutons
- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. L’effet peut être apparaître au survol au lieu du clic.

#### Page d’accueil
-  Créartion d'un “loading spinner”. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran.

#### Pages de menu
- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”.
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. L’effet peut apparaître au survol au lieu du clic.  

### Identité graphique
#### Polices :
**Logo & titres**: Shrikhand   
**Texte**: Roboto  
#### Couleurs:   
- **Primaire**: #9356DC
- **Secondaire**: #FF79DA
- **Tertiaire**: #99E2D0
