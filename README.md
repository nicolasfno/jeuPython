#   au lancement arriver sur un menu avec 3 choix 
    #   verifier si la db repond bien 
    #   lancer une partie 
    #   tableau des scores 
    #   quitter le jeu

#   au lancement de la partie 
    #   demander un username 
        #   recuperer input
        #   verifier si input valide

    #   choisir 3 personnage parmis une liste venant de mongodb
        #   afficher la liste 
        #   recuperer les heros depuis la db 
        #   recuperer input du choix valide
        #   creer l'objet hero 

#   gerer les vagues et les combats 
    #   commencer a la vague 1
    #   tant que notre hero est vivant :
        #   piocher aleatoirement un ennemi dans la db 
        #   creer l'objet enemy 
        #   afficher le debut du combat 

        #   boucle du combat tant que hero vivant et ennemi vivant:
            #   tour des heros :
                #   heros attaque ennemi 
                #   afficher l'attaque et les degats 
                #   delay pour qu'on voit l'action 
                #   si ennemi meurt casser la boucle du combat

            #   tour ennemi :
                #   ennemi attaque hero 
                #   afficher attaque et les degats 
                #   delay 

        #   si ennemi battu :
            #   monter au numero de vague suivant

#   mort des personnages game over 
    #   calculer le score 
    #   afficher game over 
    #   sauvegarder le score et username dans mongodb 
    #   attendre que l'utilisateur appuie sur entree 
    #   retour au menu principal 



