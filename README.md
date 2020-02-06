# Standards à mettre en place
 
Bienvenu sur le projet

## Installation du projet

Avoir node.js et npm d'installer sur le projet :

 - Npm version `6.13.4`
 - NodeJs version `12.14.1`

## Les commentaires

## API
Les routes d'API devront respecter la norme [REST](https://restfulapi.net/resource-naming/)

# Les règles en front 

### Standards javascript

Le projet se base sur [JavaScript ES6](https://github.com/elierotenberg/coding-styles/blob/master/es6.md)

Le projet se base aussi sur TypeScript pour éviter les erreurs de typage.

### Standards du style

Le projet se base sur [SASS](https://sass-lang.com/documentation)


# Les règles en back 

### POO et Programmation fonctionnelle

La programmation orientée objet amène un code modulaire.

# Github

Le projet contient un travis et un git flow.

### `/master`

Ne jamais se mettre sur la branche master pour développer. Pour récupérer les modifications faites sur la branche developer.

Aller sur develop, faite vos modification. Un git flow est mise en place, créez votre release pour ajouter les modifications sur le prod.

### `/develop`

La branche develop permet de mettre à jour la prépoduction sur heroku.



## Sécurité

Toujours respecter le [OWASP Top 10](https://www.httpcs.com/fr/top-10-owasp).

# Infrastructure

L'infrastructure va compter plus de 10 000 utilisateurs connectes en simultané.

## Les choix

### Serveur

Nous avons choisis d'utiliser AWS Cloud, il permet de s'adapter au nombre d'utilisateur qui vont être connecté.

### Base de données

Nous utilisons une base de données NoSQL, elle permet de dispatcher les charges de travails sur les différents serveurs

### Les librairies utilisés

Les seuls dépendances autorisés sont  `express`,  `passport`  et  `websocket`  ou  `socket.io`.

### Base de données

### Queue

### Sysadmin

### Monitoring

