EXERCICE n°2 :   
Vous allez créer un nouveau projet sur votre dépot git.   
Vous allez appeler votre projet “exercice2”.   
Ci-dessous les étapes à effectuer :
● En local, vous allez un projet exercice2, vous allez ensuite
récupérer un projet présent sur git.   
● Il vous faudra utiliser la commande “git clone”.   
● Le lien du dépot à cloner est :
https://gitlab.com/mohamed.formation.m2I/m2iformation_exo.
git   
● Il s’agit d’un site web pour publier votre CV.   
● Il faudra modifier le fichier html pour faire apparaître vos
informations personnels sur le CV.   
● Une fois que vous avez modifié ce CV, il faudra effectuer les
opérations nécessaire pour pousser sur votre dépôt distant
(exercice2) la version modifié du site.   

git init   
git clone https://gitlab.com/mohamed.formation.m2I/m2iformation_exo.git   
add ./README.md   
commit -m "Commit 1 Exercice2"   
git remote add origin https://github.com/VincentLip/Exercice2.git   
git branch -M main   
git push -u origin main   
remote set-url origin https://github.com/VincentLip/Exercice2.git   
git remote add origin https://github.com/VincentLip/Exercice2.git   
git branch -M main   
git push -u origin main   
