
# tpFormation

Ceci est un petit tp de formation pour une gestion de plusieurs organismes scolaire. 
Gestion d'organisme, candidat, formateur, salle, session, etc...

Pour initialiser le projet: 

```bash
composer install
npm install
docker-compose up -d
````

Pour faire tourner le projet il vous faut faire les commandes suivantes et les faires tourner en fond:
```bash
npm run watch
symfony serve
```

Ensuite dernière commande pour initialiser la bdd:
```bash
php bin/console doctrine:migrations:migrate
````
Vous voila enfin prêt à explorer le projet