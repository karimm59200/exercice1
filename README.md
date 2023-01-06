# exercice1

exercice 1 dans le cadre du TP apprentissage de git : 

Exercice n°1 :
Vous allez créer un projet sur votre dépot git.
Vous allez appeler votre projet “exercice1”
Ci-dessous les étapes à effectuer :
● En local, vous allez créer un projet qui sera composé d’un
fichier texte, qui s'appellera “fichier1” dans lequel vous saisir
le texte suivant :
○ Je suis l'exercice 1 de “votre prénom".
● Il faudra faire en sorte que ce fichier soit présent sur votre
dépôt distant sur git dans votre projet “exercice1”.
● une fois que cela aura été fait, il faudra créer un nouveau
fichier texte que l’on va appeler “fichier2”.
● Ce nouveau fichier devra contenir le texte suivant :
○ Je suis l'exercice 1 mais je suis le second fichier
● Ce fichier qui s’appelle fichier2 sera lui aussi pousser sur votre
dépôt distant au sein de votre projet “exercice1”.




Voici les étapes pour la réalisation de l'exercice:

je crée le dossier que je nomme exercice1-tpGit que j'ouvre depuis mon gitBash. je me rends sur github et je clique sur la crois pour la création d'un new repository. 
Je copie et colle dans mon terminal : 
echo "# exercice1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/karimm59200/exercice1.git
git push -u origin main 

je me rends sur mon dossier exercice1-tpGit que j'ouvre depuis avec VScode et je crée le fichier1.....

je retourne sur git bash et je fais un git status. Je vois le fichier 1. Je l'ajoute avec git add et je commite avec git commit -m et j'oublie pas le message pour le commit.

 je le pousse sur le repos distant avec la commande git push.

je recommence l'opération avec le fichier 2. 

je crée le fichier, je le modifie et je le add git add , git commit -m et git push sur le repos distant. 
