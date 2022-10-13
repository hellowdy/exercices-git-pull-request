#Pull request

### Fork et clone le dépôt
Créer un dossier __exercice-git-pull-request__ 
Se positionner dans le dossier.

Fork le dépôt upstream sur votre dépôt origin.

Créer un dossier puis faites :
```sh
git clone  # copie l'URL
```


Puis créer une nouvelle branche  :
```sh
git branch # nom de la branche
```

Aller sur la nouvelle branche :
```sh
git checkout # nom de la branche
```
Allez dans le fichier exercice.md
Cocher votre prénom


# Push de votre local et ajoute la nouvelle branche sur github
La branche existe sur le dépôt local mais pas sur votre dépôt distant github. Pour pouvoir ajouter une nouvelle branche et mettre à jour le dépôt distant. Faire la commande suivante :
```sh
git push --set-upstream origin #nom de la branche
```

