# Hello la Bastille! 
## Pour récupérer ce repertoire
- Récupérer le lien du repertoire: https://github.com/jc-aziaha/bastille_symfony_blog.git
- En local dans le dossier bastille, taper la commande: git clone https://github.com/jc-aziaha/bastille_symfony_blog.git symfony_blog
- Charger le dossier 'symfony_blog' avec VsCode
- Taper la commande: composer install
- Dupliquer le fichier .env
- Le ronner en .env.local
- Y configurer les pilotes pour se connecter à la base de données
- Créer la base de données: symfony conbsole doctrine:database:create
- Migrer les données: symfony conbsole doctrine:migrations:migrate
- Démarrer le serveur: symfony server:start
- Charger l'application dans le navigateur https://localhost:8000
