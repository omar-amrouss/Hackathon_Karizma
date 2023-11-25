# Hackathon_Karizma
Objectif du Projet : Développer une mini-application de partage de recettes de cuisine avec une partie back-end et une partie front-end, en utilisant Laravel


instruction:

télécharger le fichier zip

1er étape: Pré-requis

Installer Laravel.

2eme étape: Installation des dépendances et packages nécessaires.

Installation des dépendances composer avec la commande : composer install

Installation des dépendances npm avec la commande : npm install

Packages utilisés :

Ces commandes ne sont pas nécessaires pour l'installation.

Installer le package https://github.com/laravel/ui avec la commande composer require laravel/ui --dev

Installer le package https://laravelcollective.com/docs avec la commande composer require laravelcollective/html

Après l'installation du package précédent, executer cette commande: php artisan ui bootstrap --auth

Mise en place de la base de donnée

La base de donnée est en principe déjà configurée et prête à être utilisée cependant vous pouvez à tout moment la réinitialiser et la re-populer avec les commandes suivantes:

php artisan migrate:fresh php artisan db:seed

Une fois toute les étapes précédentes effectuées vous pouvez à présent lancer le serveur local avec la commande : php artisan serve
Il ne vous restera plus qu'à aller sur http://127.0.0.1:8000/ pour visiter le site web.

Pour vous connecter en tant qu'administrateur il vous suffit de rentrer ces identifiants :

email : admin@admin.com

password: adminadmin

Pour vous connecter en utilisateur alpha, vous pouvez créer un utilisateur via le bouton 'register'.
