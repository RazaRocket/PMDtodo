# PMDtodo
Projet de cours basé sur le site todomvc.com

<br>
## User stories
Définition des actions de l'utilisateur:
- [] En tant qu'utilisateur je peux ajouter une tâche
- [] En tant qu'utilisateur je peux valider une tâche
- [] En tant qu'utilisateur je peux supprimer une tâche
- [] En tant qu'utilisateur je peux afficher les tâches réalisées
- [] En tant qu'utilisateur je peux afficher les tâches réalisées
- [] En tant qu'utilisateur je peux supprimer toutes les tâches réalisées

## Mise en place du projet
Étapes à suivre pour préparer le projet PMDtodo
- [ ] Initier un serveur Nodejs
- [ ] COnfigurer la BDD MOngoDB
- [ ] Créer une route `front` pour afficher un fichier `index`dans un dossier `www`
- [ ] Créer une route `api`qui renvoier en `json`l'objet `{ msg: 'Hello API'}`

## Configurer la base de données
Le but est de définir le-s model-s de données à utiliser pour l'application
- 1. Combien d'informations faut-il enregistrer pour une tâche?
- 2. Comment une tâche est validée ?
- 3. Comment une tâche est supprimée?
- 4. Comment les tâches sont filtrées?

<br>
### 1. Combien d'informations faut-il enregistrer pour une tâche?
il faut 3 informations:
- _id: string
- Etat: boolean
- Contenu: string

<br>
### 2. Comment une tâche est validée ?
Quand la propriété `état` est égale à `true`

<br>
### 3. Comment une tâche est supprimée?
Chaque tâche présente un bouton qui, au clic, permet de supprimer l'objet
- [ ] je dois connaître la propriété `_id` de l'objet
- [ ] Créer une route `api` pour supprimer l'objet de la base de données

<br>
### - 4. Comment les tâches sont filtrées?
Je dois sélectionner tous les objets et n'afficher que ceux dont la propriété `state`est égale à `true`(ou `false`)
- [ ] Créer une route `api`pour supprimer

