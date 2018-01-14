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
    Mail 
    Adresses de livraison 
    email 
    numero de téléphone

Commandes 
==========
    Identifiant command  master
    Identifiant command
    Provider 
    Identifiant externe 
    Liste des Command items 
    Liste de colis
    Statut
    Liste de documents(Factures, Photos, ...) 
    Valeur 

Command Items
=============
    Identifiant command 
    Nom Item
    Description Item
    Quantité 
    Prix Unitaire   
    Devise 



Colis 
======
    Identifiant colis
    Identifiant command
    Longueur 
    Largeur
    Hauteur 
    Poids Volumetrique
    Supplement Hors Gabarit
    Valeur
    Devise
    Liste de Colis Items

Colis Items
===========
    Identifiant command 
    Nom Item
    Description Item
    Quantité 
    Prix Unitaire   
    Devise 

    
Expedition 
===================
    Expedition Id
    Transporteur:
    Lieu Depart  
    Lieu Destination
    Date de Depart 
    Date Arrivée estimée
    Date Arrivée effective
    Liste de Box
    Liste de documents(Factures, Photos, ...)  

Box 
===
    Box Id    
    Expedition Id
    Longueur 
    Largeur
    Hauteur
    Poids
    Liste de Box Items


Box Item (Box Id + Colis)
========
    Box Id
        Colis.Longueur 
        Colis.Largeur
        Colis.Hauteur
        Colis.Poids
        Colis.Valeur
        Colis.Supplement Hors Gabarit 
        Colis.Command Id
    Commentaire





### Commentaires 
    
    Suite à vos retours:
  
    L'enrichissement des providers se fera au fur et à mesure.
    Une command est composée d'une command master et de 'sous-commandes' par Provider.
    Le client n'a plus d'adresse postale
    Super retour sur la notion de colis. Je ne l'avais pas en tête!
    Pour les expeditions : 
        Ajout de d'informations complementaires : ville de livraison, numero d'expediion, date expedition,... 
        Les expeditions sont composées de box 
        Les box sont eux même composés de box items (colis ....)  
        Les box items (colis) sont reliés aux commandes
    
    Vos inputs éclairés sont les bienvenus!

### Fonctionalités 
    Pour l'instant, on peut penser aux fonctionalités suivantes :
    1 - Base de données centalisée des commandes 
    2 - Suivi des commandes 
    3 - Outil de suivi de commandes (portail web, envoi de textos en auto etc...)
    4 - Outil de facturation 
    5 - Historique, statistiques, etc...




