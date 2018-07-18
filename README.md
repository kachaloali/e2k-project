# ✨  e2k-project ✨

[![chat][chat-badge]][chat]
[![Build Status][build-badge]][build]
[![version][version-badge]][package]
[![MIT License][license-badge]][LICENSE]



Voilà la procédure pour installer le serveur xampp et inserer wordpress dedans

1. Il faut le télécharger à l'adresse : https://www.apachefriends.org/fr/download.html.
version pour linux
2. Le fichier télécharger doit avoir ce nom là : xampp-linux-x64-7.2.7-0-installer.run
3. Il faut se donner le droit d'exécution de ce fichier : > sudo chmod +x xampp-linux-x64-7.2.7-0-installer.run
4. Exécuter le en ligne de commande : > ./xampp-linux-x64-7.2.7-0-installer.run et suivre les instructions
5. Après l'installation demarrer le serveur lampp: >sudo /opt/lampp/lampp start
6. Pour tester si le serveur est en actif, demarrer un navigateur et taper l'adresse : localhost/
7. Creer une base de donner à travers phpmyadmin



8. Télécharger wordpress : https://fr.wordpress.org/download/
9. Décompresser le et ajouter le dans le dossier /opt/lampp/htdocs/
10. Il y a un fichier qui s'appelle wp-config-sample.php dans /opt/lampp/htdocs/wordpress/,
copier ce fichier dans un autre fichier que vous appelerez obligatoirement wp-config.php
11. Si le fichier wp-config.php est crée, éditez le en donnant le nom de la base que vous veniez de créer,
lutilisateur : "root" et mot de passe : ""

12. Tester si wordpress marche: dans le navigateur saisir : localhost/wordpress/

