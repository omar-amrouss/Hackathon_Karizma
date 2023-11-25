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
