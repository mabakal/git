#### C'est quoi git et gitHub?
GitHub est une plateforme de développement logiciel basée sur le cloud, qui utilise le système de contrôle de version Git.
Git est un système de contrôle de version, souvent utilisé pour le développement de logiciels, mais également pour la gestion de versions de tout type de fichiers.
Git permet à plusieurs personnes de travailler sur un même projet simultanément et de suivre l'historique des modifications apportées aux fichiers du projet.
Voici quelques fonctionnalités principales de Git :

- Suivi des modifications : Git enregistre les modifications apportées aux fichiers, ce qui permet de suivre l'évolution d'un projet au fil du temps.
- Branches : Git permet de créer des branches, des versions parallèles du code source, ce qui facilite le développement de fonctionnalités séparément sans perturber la version principale du projet.
- Collaboration : Git facilite la collaboration entre plusieurs développeurs en permettant le partage des modifications sur un serveur distant.
- Historique : Git conserve un historique complet de toutes les modifications apportées aux fichiers, ce qui facilite le suivi des changements et la résolution des conflits.

#### Utilisation de git

 Si Git n'est pas déjà installé sur votre système, vous devez l'installer. Vous pouvez télécharger Git depuis le site officiel : [git site web](https://git-scm.com/downloads)

 Une fois vous l'avez installer vous pouvez commencer par utiliser en creant votre propre projet ou en collaborant sur un projet. Il y a plusieur commande voici quelque uns pour débuter

 #### Creer son propre projet

 Créer votre projet par votre éditeur préférer. Dand la racine de votre projet mettez cette commande : 

 ```zsh
 cd dossier_de_votre_projet
```
dans cette dossier tu tapes les commande suivant
```zsh
    git init
```
Apres avoir travailler sur ton projet, pour l'envoyer sur ton compte git tu fait comme cece

```zsh
    git add remplace_par_le_nom_de_fichier
    git commit -m "remplace ton message"
    git push
```

 #### Comment télécharger un porjet sur ton local?

Sur tu veux télécharger un projet sur ton local, fait comme ceci
Identifier premierement l'url du projet á télécharger, apres tu le clone

```zsh
    git clone url_du_projet
```
