# OC-Brain Storming

Provider (Ex:Amazon, ...)
=========================
    Id Interne
    Addresse 
    Numero de téléphone
    Addresse
    email


Client
=======
    Identifiant interne
    Nom 
    Prenom 
    Date de Naissance 
    Adresse Postale 
    Mail 
    Adresses de livraison 
    email 

Commandes 
==========
    Provider 
    Identifiant externe 
    Liste des items 
    Liste des expeditions reçues 
    Statut
    Liste de documents(Factures, Photos, ...) 
    Valeur 




Expedition (Colis)
===================
    Expedition Id
    Source  (Extern/Intern)
    Transporteur:
    Lieu Depart  
    Lieu Destinée
    Date de Depart 
    Date Arrivée estimée
    Date Arrivée effective
    Commande Associée
    Liste de documents(Factures, Photos, ...)  


### Commentaires 
    Un point important serait de mettre à jour la base de données de vos clients, Provider et Transporteur
    Ensuite, viendront les commandes, expeditions, des l'ensembles de produits concernés)
    Pour l'instant on peut penser aux entités (type de données que nous aurons à gérer) listée plus haut. 
    /!\ N'hésitez pas à remonter d'autres informations que nous devrons sauvegarder.
    Il faudra aussi penser à un outil de génération de fichiers pdf pour les factures ...



### Fonctionalités 
    Pour l'instant, on peut penser aux fonctionalités suivantes :
    1 - Base de données centalisée des commandes 
    2 - Suivi des commandes 
    3 - Outil de suivi de commandes (portail web, envoi de textos en auto etc...)
    4 - Outil de facturation 
    5 - Historique, statistiques, etc...




