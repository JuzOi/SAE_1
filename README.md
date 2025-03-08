# Implémentation d’un besoin client  
# Gestion d’interventions fibre optique

## Présentation de l’application

L'application vise à gérer les demandes d'interventions pour des installations et dépannages chez des particuliers. Elle offre un système complet permettant d'inscrire des entreprises (opérateurs, agents, etc.) et de gérer les différentes missions, de leur publication à leur accomplissement. Elle permet à des agences et intervenants de consulter, répondre et réaliser ces demandes. De plus, l'application prend en charge la sous-traitance de missions, les rapports associés, et fournit des récapitulatifs pour évaluer l'état des missions.
•	Inscriptions : Permet l'inscription de différentes entreprises (OP, AG, IN) avec un nom associé. 
•	Gestion des missions : 
- Attribution de missions avec des niveaux de rémunération. 
- Consultation des missions disponibles. 
- Affichage des détails d'une mission spécifique. 
- Acceptation des missions par les opérateurs (OP).
•	Sous-traitance : Possibilité de sous-traiter des missions à des agences (AG). 
•	Rapports : Gestion des rapports associés aux missions. 
•	Récapitulatif : Affichage d'un récapitulatif des missions pour une entreprise spécifiée, incluant celles non attribuées, attribuées, terminées, à réaliser et réalisées.
Entrées :  
•	Les utilisateurs fournissent des commandes sous forme de chaînes de caractères pour effectuer des actions telles que l'inscription, la création de missions, la consultation, etc.
Sortie :
•	L'application produit des messages de confirmation ou d'erreur en fonction des actions de l’utilisateur.
•	Les détails des missions, y compris les rapports associés, sont affichés lors de la consultation et des détails des missions.
•	Les récapitulatifs fournissent une vue d'ensemble de l'état des missions pour différentes catégories (les missions non-attribuées, attribuées, terminées, etc.). 

À noter que le programme ne passer pas le sprint 4 donné par notre chargé de TD, car dans le sujet, la définition des missions attribuées pour la charge C8-récapitulatif pouvait porter à confusion. Il est noté que les missions publiées par une entreprise, attribuées à une autre mais non encore terminées font parties de la section ‘attribuee’. Or les missions publiées par une entreprise et attribuées à celle-ci doivent aussi faire partie de la section ‘attribuee’, si on en croît le fichier out du sprint 4. On a corrigé le problème.
