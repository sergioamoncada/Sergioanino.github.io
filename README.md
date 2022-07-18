# Sergioanino.github.io

## add upstream

# upstream sur la console : ajout du commit sur github de l'<origin repo> suite sur le fork : update fork.

- 1 : Vérifier les branch, origin & remote.
  - 1.1 : git branch -a
  - 1.2 : git remote -v

## C'est un remote qui sert à chercher seulement de l'information des autres collaborateur avant d'un git pull.

- 2 : Crée branche -> upstream : ÊTRE sur le fork : l'autre repo <sergioamoncada>

  - 2.1 : git remote add upstream <repo original = urlGitHub original repo avant le fock>
  - 2.2 : git remote -v
  - git : git fetch upstream

- 3 : Apporter les changements sur notre repo original avant fork.
  - 3.1 : git pull
  - 3.2 : git pull upstream <branch à apporter les donnée> main

### Feature branch : pull request et merge de ma branch vers main. : fux de travail.

- git status ou git s
- créer la branch : git checkout -b feature-nino
