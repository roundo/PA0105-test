# PA0105-test
tuto

Pour git, parce que c'est compliqué

On ouvre le terminal, et on peut utiliser les commandes UNIX ( sur windows c'est pas les memes commandes )

déjà il faut naviguer dans nos dossiers: 

> dir est la fonction qui permet de regarder ce qui ce trouve dans le dossier actuel
> cd $path est la fonction qui permet de changer de dossier ( ../ pour sortir )
> mkdir $name est la fonction pour créer un dossier
> clear permet de vider la console

grace a ca on peut aller dans document, créer un dossier, rentrer dans ce dossier, et c'est maintenant qu'on va pouvoir jouer avec GIT 

donc une fois dans notre dossier: 

> git init pour initialiser 

ensuite on crée un fichier texte ou ce que vous voulez et on le met dans le dossier

> git status a utiliser tout le temps pour verifier l'etat du dossier git, ici vu qu'on a crée quelque chose dans le dossier mais qui n'appartient pas encore au projet, il va me dire que j'ai un fichier qui n'est pas tracké

on souhaite maintenant l'ajouter au projet pour que ca aille au serveur 

> git add $file/folder  permet d'ajouter dans le projet 

git commit -m "$your message" git commit permet de preparer un envoi sur le répertoire distant le "-m" nous dis que la prochaine chose qu'on ecrit est le message de commit qu'il faut mettre entre double quotes 

Si vous n'etes pas encore loggué faut que vous renseignez des infos sur vous grace a ces deux fonctions 
 > git config --global user.email "you@example.com"
 > git config --global user.name "Your Name"

une fois connecté il faut que vous refassiez le git commit qui a été interompu

le commit est parti, il faut maintenant que l'on connecte notre repertoire git a celui a distance qu'on a créé sur github 


