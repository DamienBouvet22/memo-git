# MEMO GIT 


## Guide Git
[Comprendre Git](https://www.grafikart.fr/formations/git)
## Markdowns
[Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
## Commandes de base
### retourner à une version précédente
git checkout (id du commit)

### revenir à la version principale
 git switch -

## Editeur de texte de Git

pour inserer du texte --> i (insert)

pour sortir de l'insert --> Esc

pour sortir de l'editeur et revenir aux commandes Git --> :Q

pour sortir de l'editeur en sauvegardant les modifications apportées  --> :X

Bravo tu es sorti du labyrinthe !!!

## Git Flow

[Intro à Git Flow](https://datasift.github.io/gitflow/IntroducingGitFlow.html)


# Memo Muzza

- git log = voir tous les commits


### Envoyer un fichier 

- git add = selectionner un fichier

- git commit -m " le commentaire à mettre " = commenter sa modif obligatoire

- git push = envoyer mon fichier

​
### Recuperer un fichier

- git pull + le nom du fichier = recuperer un fichier sur github

​
### Faire un tag sur un commit juste après le commit 

- git tag -a + le nom du tag ex : v1.0 + -m " ma version v1.0" = creer un tag pour un commit

- git show v1.0 = montre ce commit

​
### Faire un tag sur un commit précis

- git log = voir les commits et choisir le numero du commit à tager

- git tag +le nom du tag +le num du commit

​
### Envoyer ses tags sur GitHub

- git push origin v1.0 = envoie que ce commit

- git push origin --tags = envoie tous les tags

​
### Revenir sur une version antérieur et à la version actuel

- git checkout + numero commit/nom du tag = on revient temporairement à la version qu'on à choisit

- git switch master = revenir à la version actuel

​
### Se balader dans notre répertoire

-  cd = revient au repertoire ex : au bureau

-  cd - = permet de revenir au répertoire précedent

-  cd .. = permet de remonter au répertoire parent (ne pas oublier l'espace contrairement à windows)

-  cd / = permet de remonter à la racine de l'ensemble du système de fichiers

-  cd /usr/bin/ = se place dans le répertoire /usr/bin/

​
### Supprimer un ou plusieur fichier sois même et mettre à jour son repositories

- supprimer le ou les ficchier

- faire git add --all = selectionner les fichiers supprimer

- faire git commit -m " j'ai supprimer des fichiers"

- faire git push = met à jours github

​
### Supprimer un dossier et ce qu'il y a dedans

- git rm -r +nom du  dossier = selectionner undossier + les fichiers à l'intérieur

- git commit -m " "

- git push = dossier supr

​
### Relier son dépot local et github

- retrouver le dossier en local et faire git init

- git add --all

- git  commit -m ""

- git remote add origin + url = faire le lien

- git push  -u origin master = envoyer les fichiers

### Utiliser VCS avec webstorm

- ouvrir le bon project à modifier dans file new project

- changer le fichier dans github

- changer notre fichier en manuel

- faire un vcs + git + commit files et cocher le commit

- ensuite faire git + push 

- faire merge jusqu'à voir les 3 tableaux

- choisir dans le tableau du milieux ce qu'on veut pour le fichier final 

- faire apply

- finir avec git + push


# Memo Matthias

/*********************************** Mémo des commandes Git & GitHub **************************/

​

							| OUVRIR EN DEMI-SCREEN POUR + DE LISIBILITÉ |

						(Glisser la fenètre sur le bord d'un côter de l'écran)


	____________________________________________________________________________________________

	|      |

	|  G   |						Liens vers la doc de GIT :

	|  I   |

	|  T   |	https://git-scm.com/book/fr/v2/D%C3%A9marrage-rapide-Installation-de-Git

	|_____//

	|

	|				Raccourci GIT :

	|

	|		- CTRL + L (rafraichi le terminal) || taper 'clear' -> ENTER

	|

	|					_______________________________________________________

	|

	|

	|  1- Liste de quelques commandes de base :

	|

	| 

	|   | cd -> change directory (changé de répertoire)

	|

	|		cd 'nomDuRépertoire qu'on veut accédé'

	|   	cd .. (Reviens au répertoire précédent)

	|

	|

	|   | mkdir -> make directory (crée un répertoire)

	|

	|   	mkdir 'le nom du dossier que l'on veut donné'

	|

	|

	|   | pwd -> present working directory (répertoire de travail actuel) -- (tape juste 'pwd')

	|

	|	| mv -> move (déplacé, renommé)

	|

	|   	mv 'nom_de_fichier_actuel' 'nouveau_nom_de_fichier' (celui-ci sera renommé)

	|		(pour se délacer, consulter la doc de GIT : lien vers celle-ci en haut du fichier)

	|

	|	| rm -> remove (retirer (supprimé))

	|

	|		rm 'nom du fichier à supprimé'

	|		rm -rf 'nom du dossier à supprimé'

	|

	|                   _______________________________________________________

	|

	|

	|  2- Liste des commandes pour créer un 'repository' (dépôt) local et l'envoyer sur GitHub :

	| 

	|

	|   (Info) (Avoir crée au préalable un repository sur Github et récupéré le lien pour lui |      envoyer le repository local Git)

	|

	|   git init // initialise GIT dans le repository

	|   git remote add origin 'lien du repository correspondant' // Fait le lien avec GitHub

	|   git push -u origin master // Fait le push vers le repository GitHub

	|   git push --set-upstream origin master // Si on a pas précisé la branche

	|

	|                   _______________________________________________________

	|

	|

	|  3- Liste des commandes étapes par étapes à suivre pour push :

	|

	|

	|   git add 'le nom de ce que l'on veut "add" '

	|   git commit -m "Déscription du commit réalisé"

	|   git push || git push 'les/l'élément à push vers GitHub

	|

	|                   _______________________________________________________

	|

	|

	|  4- Liste des commandes pour cloner un repository de GitHub vers Git :

	|

	|

	|	(Info) (Ne pas oublié après avoir cloner, de changer de répértoir pour effectuer des    |      commandes (Voir la '1- liste des commandes de base' plus haut))

	|

	|   git clone 'lien du repository GitHub'

	|

	____________________________________________________________________________________________

