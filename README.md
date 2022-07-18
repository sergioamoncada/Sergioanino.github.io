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

# Feature branch : pull request et merge de ma branch vers main. : fux de travail.

- git branch ou git branch -a
- git status ou git s
- créer la branch : git checkout -b feature-nino

## push la branch

- git push : ne va pas fonctionner mais il va nous indiquer la procedure à suivre.
- git push --set-upstream origin feature-nino

### les prochaine fois on ne sera pas obliger de faire la longue commande :

- git commit -am "notre commit explication"
- git push

* suite du pull request fait sur github.

## effacer une branch feature.

- L'effacer sur github : par contre elle ne s'efface pas sur le repo local.
- 1 : git branch
- 2 : git checkout main
- 3 : git pull ---> cela va apporter tout les changements de github.

\*\* effacer la branche feature ou autre :

- git brach -d feature-nino si jamais on veut le force d'efface à la force car il y a des commit ou des changements en suspend pas nécessaire. git brach -d feature-nino -f

# apporter des tout les branches des autre collaborateur :

- git pull
- git pull --all --> cas que la brach d'un autre collaborateur n’apparaît pas!
- git branch -a

* Bouger vers l'autre brach d'un collaborateur.

- git checkout <nomBranch>
- git commit -am "notre commit explication"
- git push

- pull request pour merge les deux branchs
