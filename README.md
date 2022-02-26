## Tribunal Populaire de bureaulogie


Ce projet N’EST PAS soutenu par la rédaction de Canard PC c’est un projet uniquement personnel


### Pour installer le machin : 

1. installez symfony <https://symfony.com/download>
1. installez yarn
2. clonez ce github
3
    A. faites `composer install` dans le dossier cloné
    B. faites `yarn install` dans le dossier cloné (peut etre remplacé par npm mais demerdez vous :D )
    C. faites `yarn build` dans le dossier cloné (peut etre remplacé par npm mais demerdez vous :D )
4. lancez le server local de dev symfony : `symfony server:start`
5. `symfony console doctrine:database:create`
6. `symfony console doctrine:schema:update`
7. vous avez un serveur de dev qui fonctionne ici : https://127.0.0.1:8000/


### TODO : 

- [ ] Expliquer le projet
- [ ] Coder
- [ ] ????
- [ ] PROFIT