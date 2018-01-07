# OC-Brain Storming


Provider:
=========
    Addresse 
    Numero de téléphone
    Addresse
    email


Client:
=======
    Identifiant interne
    Nom 
    Prenom 
    Date de Naissance 
    Adresse Postale 
    Mail 
    Adresses de livraison 
    email 

Commandes: 
==========
    Provider 
    Identifiant externe 
    List des items 
    List des expeditions recus 
    Statut
    Liste de documents(Factures, Photos, ...) 
    Valeur 


:Expeditions (Une base de données des expeditions et des l'ensembles de produits concernés)


Expedition (Colis)
============
    Expedition Id
    Source  (Extern/Intern)
    Transporteur:
    Lieu Depart  
    Lieu Destinée
    Date de Depart 
    Date Arrivée estimée
    Date Arrivée effective
    Commande Associée:
    Liste de documents(Factures, Photos, ...)  


### Commentaires :
Peut-être qu'un point important est mettre à jour la base de données de vos clients, Provider et Transporteur ...
D'apres ce que j'ai les entités (type de données que nous aurons à gérer) :
Il faudra aussi penser à un outil de génération de fichiers pdf pour les factures ...



### Fonctionalités 
    1 - Base de données centalisées des commandes 
    2 - Suivi des commandes 
    3 - Outil de suivi de commandes (portail web, envoi de textos en auto etc...)
    4 - Outili de facturation 
    5 - Historique, statistiques, etc...




