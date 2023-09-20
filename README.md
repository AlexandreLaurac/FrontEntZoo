# FrontEntZoo

### Objet
Ce dépôt contient le code écrit lors des TP du module de Front-end suivi en licence professionnelle et consacré à HTML/CSS/Javascript. Le but de ces TP était de réaliser un mini site de voyage, de sport ou de zoo (ce dernier ayant été choisi).  

### Commits
Les cinq commits correspondent aux différents TP, le dernier TP étant constitué de deux parties :
- TP1 : site avec code HTML seul
- TP2 : ajout de règles CSS
- TP3 : ajout de code JavaScript pour la création dynamique du menu et du tableau d'animaux, ainsi que l'affichage des différents onglets
- TP4, partie 2 (traitée en premier) :
  * persistance des données du tableau d'animaux
  * système de connexion minimaliste
- TP4, partie 1 : responsive web design par ajout de règles de style dépendant du format de l'appareil (à tester sous Firefox par clic sur ctrl-maj-m et modification de la taille de la fenêtre)

### Consultation
Dans les trois premiers commits, le site peut être consulté directement par ouverture des pages HTML disponibles dans un navigateur. A partir du commit du TP4, partie 2, il convient de réaliser les actions suivantes :
- lancer un serveur local avec la commande `php -S localhost:8080` (installation de PHP nécessaire)
- se rendre sur la page d'accueil du site avec le navigateur de son choix en lui fournissant l'adresse http://localhost:8080/accueil.html
- pour se connecter au site, se rendre sur l'onglet "Espace personnel" du menu de navigation puis saisir l'identifiant et le mot de passe "user" et "ajax" pour un utilisateur quelconque, "admin" et "ajax" pour l'administrateur.  
Dans le premier cas, une fonctionnalité supplémentaire de zoom de la photo des différents animaux est disponible dans le tableau de la page "Animaux" (pour cela, cliquer sur "Découvrir" puis survoler la photo de l'animal correspondant).
Dans le second cas, il est possible de modifier et de supprimer les différents animaux du tableau, ainsi que d'ajouter un nouvel animal à celui-ci.
