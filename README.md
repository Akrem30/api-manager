# api-manager
api-manager est une API RESTful développée en Node.js qui permet de créer, mettre à jour et supprimer des tâches à réaliser (Lien vers l'api : https://content-api-3be8.onrender.com/). 
Une fois qu'une tâche est activée, un compte à rebours se déclenche pour montrer combien de temps il reste pour terminer la tâche.

## Fonctionnalités
-Créer, mettre à jour et supprimer des tâches.
## Routes
-GET api/resources - Récupérer toutes les tâches.

-GET api/resources/id - Récupérer une tâche par son id.

-POST api/resources - Créer une nouvelle tâche.

-PUT api/resources/id - Mettre à jour une tâche par son id (pour activer une tâche, il suffit de mettre à jour sa propriété status à 'active').

-DELETE api/resources/id - Supprimer une tâche par son id.
