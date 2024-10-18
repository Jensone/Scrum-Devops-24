# Gestion Restaurant

## CàD. Entité ou Organisation

Gestion des tables et réservations :

- En tant que HÔTE
- Je veux ACCEDER à la liste des tables
- Afin d'AJOUTER une réservation
    
- En tant que HÔTE
- Je veux LIBERER une table
- Afin d'ACTUALISER la liste des tables

Gestion du menu :

- En tant que HÔTE
- Je veux MODIFIER les plats
- Afin de METTRE À JOUR le menu

Gestion des stocks :

- En tant qu'EMPLOYÉ DU RESTAURANT
- Je souhaite ACCEDER au stock 
- Afin de CONTRÔLER le niveau des produits

Gestion du personnel :

- En tant qu'EMPLOYÉ DU RESTAURANT
- Je peux ACCEDER à mon planning
- Afin de CONNAÎTRE mes heures de travail

Analyse des ventes :

- En tant GESTION ADMINISTRATIVE
- Je suis ALERTÉ lors du dépassement de CA de 10% par rapport à la semaine passée
- Afin de METTRE EN PLACE une stratégie d'aquisition client

---

# Expérience Client

## CàD. Humain

Recherche de restaurants :

- En tant que CLIENT
- Je VEUX une interface de recherche
- Afin de TROUVER un restaurant

Réservation :

- En tant que CLIENT
- Je souhaite FOURNIR les informations via un formulaire
- Afin de VALIDER ma réservation

Commande en ligne :

- En tant que CLIENT
- Je veux CHOISIR le mode de paiement
- Afin de VALIDER ma commande

Programme de fidélité :

- En tant que CLIENT
- Je veux ÊTRE récompensé pour mes commandes
- Afin d'OBTENIR des réductions

---

# Administration Système

## CàD. Machine / Application (API, Micro-Service)

Sécurité :

- En tant que SYSTÈME
- Je veux CONTRÔLER l'accès à l'application
- Afin de GARANTIR le bon fonctionnement de l'application

Intégration des paiements :

- En tant que SYSTÈME
- Je veux ACCEDER à une API de paiement
- Afin d'ENCAISSER les clients

Notifications :

- En tant que SYSTÈME
- Je dois EMETTRE une notification de nouvelle commande
- Afin d'INFORMER le restaurant

Rapports :

- En tant que SYSTÈME
- Je dois GÉNÉRER un rapport d'activités
- Afin d'INFORMER le restaurant

---

# Exemple pour trier les US 

En tant que conducteur,
Je veux pouvoir indiquer le type de véhicule que j'utilise (électrique, hybride, essence)
Afin que les passagers soucieux de l'environnement puissent faire leur choix en connaissance de cause.

Critères d'acceptance (approche initiale):

- Est-ce l'US repose sur une seule action ?
- La rédaction est-elle claire et simple ?
- S'agit-il, une action dans un ensemeble ou qui doit être segmentée ?

Critères d'acceptance (approche projections technique):

1. Le conducteur peut sélectionner le type de son véhicule parmi une liste prédéfinie
2. Le type de véhicule est visible dans les résultats de recherche
3. Un badge "véhicule vert" est automatiquement attribué aux véhicules électriques et hybrides
4. Le conducteur peut modifier le type de véhicule dans son profil
