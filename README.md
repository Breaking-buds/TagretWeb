# TagretWeb
Réalisation d'un test de compétences


Pour ce test, j'ai utilisé un plugin ACF Pro (en version nulled, ne me dénoncez pas SVP) et le classic editor de WP.

J'ai pour habitude d'utiliser sur mes travaux le compileur de CSS SASS.

N'ayant pas l'habitude de travailler sur Github je n'ai pas pris en main l'initiation de mon projet en local, je manque un peu de temps pour l'appliquer à ce projet avant le Lundi 15. 

Je me permet d'upload mes fichiers en ZIP sur mon repository.

Mon thème wordpress est très simple et utilise quelques fonctions natives de wordpress.
On y trouve une fonction pour le Walker menu, une focntion permettant d'afficher un "excerpt" d'un Fiel ACF, des fonctions pour enlever les commentaires wordpress et les quelques autres fonctionalités qui ne servent pas à ce projet. 

J'ai crée le custom post type Recette directement dans le function.php même si j'ai l'habitude d'utiliser le plugin CPT UI.

Pour installer le projet sur votre machine en local, il suffit de l'ajouter à votre serveur virtuel, pour ma part c'est Wamp.
Il suffira de changer les informations de connexion à la base de donnée dans le fichier wp-config, d'importer la base dans votre phpMyAdmin en changant s'il le faut les lignes "siteurl" et "home". Une fois ces modifications éffectuées, vous pourrez vous connecter à l'admin à l'adresse http://localhost/targetWebTest/wp-admin/.

Allez ensuite dans réglage -> permaliens et appuyez sur "enregistrer les modifications"

J'aurais aimé queqlques améliorations sur le projet d'un point de vue design en étoffant la page avec d'avantages d'inforamations.
Pour un réel site de recettes, j'aurais aimé prévoir un espace utilisateur avec la possibilité de soumettre des recettes personelles, laisser des avis et des notations. 
Il aurait été agréable d'ajouter un slider d'images pour chaque recettes pour donner l'eau à la bouche !

