Tuto Git:
==
<br/>-télecharger Git 
<br/>-Connecter vous depuis le site github
<br/>-ouvrir le projet avec clique droit git bash here
<br/>-inialiser le projet avec la commande git init
<br/>-configurer notre projet avec la commande git config --global user.name tuto_git
<br/>-on fait la meme chose mais pour Email git config --global user.email adriencharmarty@gmail.com
<br/>-pour voir s'il y a eu des changements dans notre dossier, git status
<br/>-pour pré-sauvegarder tout nos dossier faire un git add . 
<br/>-puis enregistrer la sauvegarde avec git commit -m "tuto_git"
<br/>-pour ignorer un dossier faire git rm --cached README.md
<br/>-on peut créer un fichier gitignore avec touch .gitignore et dedans mettre le dossier qu'on veut ignorer
<br/>-pour récuperer un fichier supprimer faire git checkout -- .
<br/>-ajouter une branche avec git branch dev
<br/>-pour voir nos branch faire un git branch --list
<br/>-pour changer de branche git checkout dev
<br/>-pour récuperer une branche inférieur avec git merge dev
<br/>-transferer notre projet sur le site, il faut une fois connecté sur le site cliquer sur la croix en haut à droite, puis new repository
<br/>-donner un nom à notre projet, puis une description et enfin cliquer sur create repository
<br/>-pour transferer notre projet sur l'ordinateur à github sur internet récuperer la ligne, git remote add origin https://github.com/AdrienCY/tuto_git.git
<br/>-puis l'autre ligne, git push -u origin master
<br/>-pour créer un readme faire, touch README.md et faire une description à l'intérieur puis git add . puis git commit -m "ajout d'un fichier README" puis faire un git push