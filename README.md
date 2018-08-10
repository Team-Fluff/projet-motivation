Mise en place

1/ Créer un compte sur https://github.com avec l'adresse où t'as reçu le lien d'invitation

2/ Télécharger GitKraken

c'est le logiciel qui permet de voir/envoyer/récupérer les changements dans le projet
https://www.gitkraken.com/download/windows64

3/Installer GitKraken et l'ouvrir

4/Se connecter dans GitKraken avec le compte GitHub

normalement c'est via OAuth, tu mets le mail et ton mdp github, une fenetre va s'ouvrir dans ton navigateur, accepte, c'est magique

5/ Récupérer le projet

Clic sur le dossier en haut à gauche dans GitKraken => Clone
- Soit GitHub.Com , sélectionne ton compte dans la liste, puis le repo "projet-motivation"
- Si il n'y est pas : Clone with Url, et tu colle ça dans "URL": https://github.com/Team-Fluff/projet-motivation.git et tu choisis le dossier sur ton PC où tu veux que le projet atterisse.

5.5/ Tu verras un arbre avec les "commits" au milieu (ce sont des lots de changements), double clique sur "develop" tout à gauche
En haut, clic sur "Pull" pour récupérer la derniere version
Dans l'arbre au milieu, l'icone local (le petit PC) et l'icone "origin" se situent sur la même ligne avec develop si t'es à jour.

6/ Télécharger et installer unity

https://store.unity.com/download?ref=personal , coche la case et télécharge l'installer pour windows

7/ Ouvrir le projet avec unity

Open => chercher le dossier "Projet Motivation" là où tu as mis le dossier "projet-motivation" avant avec gitKraken

8/ Configurer Unity

Edit -> Project Settings -> Editor, une fenetre s'ouvre
Dans cette fenetre s'assurer que
- Version Control/Mode soit à "Visible Meta Files"
- Asset Serialization/Mode soit à "Force Text"

9/ Contribuer au projet

Quand tu fais des changements dans unity, ou plus globalement dans le dossier  "projet-motivation" depuis n'importe quel programme (ajout d'images etc...), une nouvelle ligne apparaitra tout en haut de l'arbre dans GitKraken, avec la liste de touts les changements sur la droite.

Pour me l'envoyer, Vérifie que les changements sont OK avec ce que tu veux envoyer "Stage all changes" à droite, Ajoute une description du changement dans "Summary", puis "Commit"

Ca créé un "Commit dans l'arbre, pour l'instant il est juste sur ton PC.

Pour me l'envoyer, Clique sur "Push" tout en haut.

De mon coté, je le récupérerait en cliquant sur "Pull"



