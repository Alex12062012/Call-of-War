# Call of War

> L'un de mes premiers projets de jeu : je voulais faire un jeu de conquête en ligne dans le style d'[OpenFront](https://openfront.io).

## Ce que contient ce dépôt

Ce sont des **fichiers récupérés du projet open source [OpenFrontIO](https://github.com/openfrontio/OpenFrontIO)** (un jeu de stratégie en temps réel dans le navigateur), que je voulais étudier et modifier. Pour certains, ce sont des versions un peu différentes de l'original :

- `index.html` : la page d'accueil du jeu ;
- `src/server/` : des morceaux du serveur (gestion des parties, playlist des cartes, aperçus de parties, journalisation) ;
- `tests/pathfinding/playground/` : une page de test du calcul de chemins ;
- `resources/` : la politique de confidentialité et les conditions d'utilisation d'OpenFront ;
- `.github/workflows/ci.yml` : la CI du projet d'origine.

⚠️ **Le dépôt ne tourne pas seul** : il manque le reste du projet (le `package.json`, le cœur du jeu dans `src/core`, le client, les cartes…). Pour jouer, il faut aller sur [openfront.io](https://openfront.io) ou cloner le dépôt OpenFrontIO complet.

Ma propre version, que j'ai écrite moi-même en Python, est dans **[Call-of-War-2.0](https://github.com/Alex12062012/Call-of-War-2.0)**.

## Crédits et licence

Le code vient d'OpenFront, publié sous licence **GNU AGPL-3.0**, © les auteurs d'OpenFront. Tout ce qui est repris ici reste sous cette licence.
