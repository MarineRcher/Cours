### Dev web

Ceci est une commande :
``` bash
    mkdir test
```

Ceci est du code :

``` Javascript
    const test = 'Hello world';
```

Le dépot git ou repository est le dossier qui contient les données que l'on souhaite visionner. On y trouve un dossier caché ".git/"

La commande `git init` permet d'initialiser un depot Git dans le répertoire courant. Se traduit par le présence d'un .git/ à la racine du dépot. 

La commande :
``` bash
    git init
```
Permet d'initialiser un dépot Git. Et sera détecter par git

Pour vérifier l'état de votre dépot Git utiliser la commande :
``` bash
    git status
```
Avant de sauvegarder les modifs, il faut ajouter les modifications que l'on souhaite sauvegarder
Pour ajouter un fichier :
``` bash
    git add <nomfichier>
```

Pour commit, c'est à dire faire la sauvegarde :
``` bash
    git commit -m "blabla"
```

Pour renommer la branche principale en main
```
git branch -M main
```

Synchronise la branche pour envoyer la sauvegarde :
```
git remote add origin <url repo>
```

Pour envoyer la dernière sauvegarde sur le repo :
```
git push -u origin main
```

Voir history:
``` bash
    git log
```

une liste d'entrées distantes stockées dans le fichier ./. git/config du dépôt :
```
git remote
```

