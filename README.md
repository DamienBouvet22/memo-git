# memo-git
## livrable module git

### Guide Git
[Comprendre Git](https://www.grafikart.fr/formations/git)
### Markdowns
[Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

### retourner à une version précédente
git checkout (id du commit)

### revenir à la version principale
git pull origin master






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

