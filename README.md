# Correction d'exercice n°3:  
## Gestion des conflits durant le merging :  
1. creation un repot et l' ajoute d'un fiche contenant du text:  
    - git init (pour un creer un depot en local)
    - en  ligne en cliquant sur le boutton repos et new
    - touch notes.txt  ("pour creer le fichier")
    - nano notes.txt  ("pour ajouter du contenus")
2. faire commit et pushez:  
   - git add . ("moidification d'etat)
   - git commit -m "add notes" ("faire entrer dans l'histoire)
   - git push origin main ("envoyer notre projet en ligne")
2. creation d'une branche conflit-test:   
   - git branch conflit-test ("pour creer la branche")
   - git checkout conflit-test("pour entre la branche conflit-test")
   - touch note.txt   ("pour creer le fichier")
   - nano note.txt ("pour ajouter du contenus")
3. faire un commit et pushez:  
   - git add . ("moidification d'etat)
   - git commit -m "add notes" ("faire entrer dans l'histoire)
   - git push origin conflit-test ("envoyer notre projet en ligne")
4. retour à la branche main et modifie le fiche note.txt faites commit:   
    - git checkout main ("pour changer la branche")
    - nano note.txt ("pour modifier le contenu")
    - git add .   ("changement d'etat)
    - git commit -m "note modify"("fair entre ddans l'shistoire)
5. Essayez de meger la branche confit-test dans main:  
    - git merge conflit-test ("pour combiner les deux branches ",on trouve une erreur apres avoir tapez cette commande)
6. pour corriger l'erreur:    
- on ouvre le fiche note.txt on gade les deux ligne