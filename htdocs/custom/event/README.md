#Module to manage event and registration in Dolibarr ERP/CRM.#

Configuration
- La Société/Institution doit être configuré
- la TVA doit être définis

Module pré-requis à activer 
- modFormStyler -> https://bitbucket.org/code42_fr/formstyler/src
- Tiers
- Factures et avoirs
- Produits
- Stock
- Paypal
- Tâches planifiés

Pour connaitre les différentes fonctionnalité de la version 1.8.6:
https://groups.google.com/forum/#!forum/module-event

INSTALLATION:

Rajouter des attributs dans:

--les produits et services: 
- Libellé: EVENT - Nombre d'unités
- Code de l'attribut: nbunitbuy
- Type:Numérique entier
- Taille: 10
- Peut toujours être édité
- Visibilité

--Utilisateurs et groupes:
- Libellé: Nombre unités restantes
- Code de l'attribut: event_counter
- Type: Numérique entier
- Taille: 10
- Position: 2
- Peut toujours être édité	
- Visibilité

--Dans l'admin du module
- Durée du cours (en minutes, heure, ...)
- Libellé: Durée du cours (en minutes)
- Code de l'attribut: duree_cours
- Type: Numérique entier
- Taille: 10
- Position: 0
- Peut toujours être édité	
- Visibilité
