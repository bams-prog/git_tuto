# Documentation du tuto GitHub avec Git

## Initialisation du dépôt


'''bash
git init 
git remote add origin SSH_REPO
'''

## Rédiger un commit

'''
Titre du commit 

Description de notre commit avec des informations sur l'évolution du projet 
'''

## Envoyer un commit sur le dépôt distant

'''
git add. 
git commit -m "Titre du commentaire"
git push origin main
'''

## Création d'une branche

'''
git checkout -b Nom_BRANCHE
'''

Pour les bonnes pratique, on va intégrer la notion de revue de code. Pour cela, on va créer une branche, faire des modifications, les envoyer sur les dépôts distant, puis créer une pull request pour demander une revue de code.