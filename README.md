# GlobalPoject2
My final project
# Myfile
"Mon premier depot distant avec l'outil Git pour mon fichier texte"
En description, il éetait question de réaliser un projetgit dans lequel l'étudiant va insérer ses informations et de le sauvegarder à la fois en local et à distant.
Pour la réalisation de ce projet, nous avons eu à utiliser l'outil Git via la console Gitbash
Dans un premier temps nous avons tot d'abord initialiser notre projet en utilisant la commande "git init"
Par la suite pour plus de securité et conformité nous avons configuré le projet en y ajouter un nom, email et adress d'utilisateur via les commandes "git config --global user.name", git config --global user.email" et "git config --global user.address"
Dans la suite du projet nous avons crée un dossier puis à l'intérieur du dossier un fichier.txt via les commandes usuelles "MKDIR" & "TOUCH" en local.
Après saisir des informations dans notre fichier texte grace à l'IDE Visual Studio Code nous avons créer une branche annexe "Development" à partir de la commande "git checkout -b _Development" sur laquelle nous avons créer un nouveau repertoire ou directory et enregistrer à l'intérieur un programme qui va stocker l'intégralité des codes du projet sous fichier.py : ce programme qui vérifie l'id puis l'authentification de connexion de l'étudiant.
Un "git add" et "git commit" on servit à la présauvegarde, l'enpaquetage et la mise à jour des données du projet.
Après cela un "git merge _master" servira pour fusionner la repartition des taches entre la branche principale et annexe.
Pour ce projet également nous avons créer en paralèlle un compte Github sur lequel nous avons créer notre repository en option "public" et copier le lien de ce repository.
En suite un "git clone _lienDuRepository_" pour associer notre projet à la plateforme Github et travailler ainsi en parralèlle. A la fin après sauvegarde finale du projet nous avons utiliser la commande "git push -u NomDuRepository master" à l'instar un "git push --set-upstream NomDuRepository master" à une fonction similaire Ceci pour importer notre projet direct en ligne et l'héberger sur notre plateforme. 
