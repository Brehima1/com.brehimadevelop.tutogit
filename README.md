# Documentation du tuto github avec git 

## Initialisation du depots

```bash 
git init
git remote add origin SSH_REPO
```

## Rédiger un commit(bonne pratique)

```
Titre du commit 

Description de notre commit avec des informations sur l'évolution du projet
```

## Envoyer un commit sur le depot distant

``` bash 
git add.
git commit -m"un commentaire"
git push origin master
```

## Création d'une branche

```bash 
git checkout -b NOM_BRANCHE
```

Pour la bonne pratique, on va intégrer la notion de revue de code, pour cela, on va créer une branche, faire des modifications, les envoyer sur le depot distant, puis créer une pull request pour demander une revue de code.
