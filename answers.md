# Answers of Jérémie Briguet JeremieTheRealOne

## Basics

### Task 1

- **`.git`** : versionnement et gestion de l’historique du projet. Donc toutes les informations de commits, de branches et de tags.
- **`img`** : stockage des ressources visuelles pour la documentation.
- **`.md`** : fichiers de documentation et description du projet en Markdown.

### Task 2

Dans le git Bash, avec la commande git status, le terminal affiche l'apparition du dossier README.md mais dans le untracked files. Aucun commit n'a été ajouté.

### Task 3

README.md est prêt à être commit et les logs n'ont pas changé.

### Task 4

Une partie du dossier README.md est prêt à être commit mais une autre partie de ce dossier doit aussi être placé en stage avant d'être commit.

### Task 5

**git log --oneline
408a56c (HEAD -> main) ADD: README file.
5da930b (origin/main, origin/HEAD) Initial commit**



**`408a56c`** : L'identifiant unique abrégé (ou **hash**) du commit.

**`main`** : Il s'agit du nom de la branche principale sur laquelle ce commit a été fait.

**`HEAD -> main`** signifie donc que `HEAD` pointe actuellement vers la branche `main`, et                             que ce commit est le dernier commit de cette branche.

`ADD: README file`, informe que ce commit a ajouté un fichier `README` au projet.

### Task 6

Le **checkout commit** permet de revenir à un commit spécifique, cela permet de ne pas modifier l'historique de la branche. Les fichiers ont été déplacé afin de ne pas les modifier.

Le **checkout main** permet de revenir à la branche principale. Donc cela a fait réapparaître les fichiers dans le dossier.

## Gitgraph

### Task 7

- **`1. develop`** : C'est une branche secondaire qui est souvent utilisée pour le développement des fonctionnalités.

- **`2. baa6795`** : Il s’agit d’un identifiant abrégé (hash) du commit. Chaque commit a un identifiant unique qui permet de l’identifier.

- **`3. Merge branch 'feature-auth' into 'develop'`** : C'est le message de commit indiquant qu'une branche appelée `feature-auth` a été fusionnée dans la branche `develop`.

- **`4 ByteMe Bob <bob.byteme@hevs.ch>`** : Il s'agit de l'auteur du commit, avec son adresse e-mail.

- **`5. v1.0.0`** : C'est une **étiquette (tag)** indiquant une version spécifique du projet. Les tags sont souvent utilisés pour marquer des versions importantes.

- **`6. Commit`**: C'est un merge de la branche feature-auth dans la branche develop par un autre utilisateur.

- **`7. feature-auth`** : C'est une branche de fonctionnalité (feature branch) utilisée pour développer une nouvelle fonctionnalité. Ce commit a été réalisé par un autre utilisateur 

- **`8. Merge`** : C'est un merge de la branche develop dans le main afin d'avoir une première version du projet.

- **9. develop** : C'est une branche secondaire comprennant tout le développement du projet. La branche a été merge dans le main pour une première version. Ensuite, des nouvelles modifications ont été ajouté. 

- **`10. Branche principale`** : C'est la branche main avec le commt initial et une version v1.0.0 du projet.

![Gitgraph](img/gitgraph.svg)