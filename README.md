# MyFirstRepository
How to work with Wordpress: 

Travailler en LOCAL:

Nous avons besoin d'un: 
Serveur local "WampServer" comme exemple.
Wordpress
* Télécharger et installer WAMP.
– Cette installation se fait par défaut dans le répertoire c:/wamp mais vous pouvez l’installer ailleurs. Il faudra juste connaître le chemin d’accès de votre installation.
* Télécharger WordPress.
– Décompresser le fichier WordPress dans le répertoire c:/wamp/www/ d’où la nécessitée de connaître le chemin d’accès de votre installation Wamp.
- Démarrez Wampserver puis Démarrez tous les services ou Start All Services si version anglaise.

![Start](http://www6.0zz0.com/2015/09/02/15/397581634.jpg)

Maintenant nous allons créer une base de données MySQL. Pour cela lancez phpMyAdmin.

![BDMySQL](http://www13.0zz0.com/2015/09/02/15/540064553.jpg)

Sous Créer une base de données, inscrivez le nom de la base de votre choix. WordPress par exemple

![BD](http://www9.0zz0.com/2015/09/02/15/384573732.jpg)

Puis cliquez sur Créer.

Maintenant avec un éditeur de texte quelconque, ouvrez le fichier wp-config-sample.php à l’emplacement suivant C:\wamp\www\wordpress.

![user](http://www13.0zz0.com/2015/09/02/15/449923957.jpg)

Et remplacer les éléments  suivantes :

votre_nom_de_bdd : par le nom de la base de donnée que vous avez choisi. wordpress par exemple.

votre_utilisateurd_de_bdd par root

votre_mdp_de_bdd : il s’agit du mot de passe de votre base de données. Si vous n’avez pas utilisé de mot de passe conserver le guillemets sans rien entre.

Ne changer pas le reste.

![user2](http://www11.0zz0.com/2015/09/02/15/120536354.jpg)

Enregistrez ce fichier sous le nom wp-config.php dans le même répertoire C:\wamp\www\wordpress.

Maintenant il suffit de finir l’installation de WordPress. Ouvrez votre navigateur Web et allez à l’adresse suivante : http://localhost/wordpress/wp-admin/install.php

L’installation de WordPress va commencer.

![WP](http://www6.0zz0.com/2015/09/02/15/783135705.jpg)

Renseignez le titre du blog, votre identifiant, votre mot de passe ( 2 fois ) et enfin votre adresse Email. Puis cliquez sur Installer WordPress.

![WP2](http://www4.0zz0.com/2015/09/02/15/141380513.jpg)

WordPress est maintenant installé en locale sur votre ordinateur. Pour avoir accès à l’administration de WordPress en locale, il faut aller à l’adresse :

http://localhost/wordpress/wp-login.php qui vous suffit de mettre dans vos favoris. Enfin, il suffit de récupérer votre base de données, votre template et vos articles.
