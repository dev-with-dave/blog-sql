# Blog

On va créer une base de données pour un blog nommé dw-blog! 🎉

## Entitées

Dans notre site on aura les entités suivantes:

- users : first_name, last_name, username, email, password, is_admin

  - first_name: chaine de caractères
  - last_name: chaine de caractères
  - username: chaine de caractères
  - email: chaine de caractères
  - password: chaine de caractères
  - is_admin: booléen

- articles : title, content, image_url

  - title: chaine de caractères
  - content: chaine de caractères
  - image_url: chaine de caractères

- categories : name, color

  - name: chaine de caractères
  - color (en héxadécimal): chaine de caractères

- comments : content
  - content: chaine de caractères

## MCD

Commencer par réaliser le MCD (on peut s'aider de MoCoDo), ne pas hésiter a regarder ce qui a été fait en cours !

## Cardinalitées

Une fois le MCD réalisé on va s'interesser aux cardinalitées pour faciliter le MLD.

- on va se demander combien de fois une entité peut participer à une relation (01, 11, 0N, 1N)

## MLD

Une fois le MCD et les cardinalitées réalisés, on va pouvoir faire le MLD et ajouter les clés (primaires, étrangères) à nos entitées.

## Création de la base en SQL

Une fois toutes les étapes ci-dessus réalisées on va pouvoir enfin créer notre base en utilisant le langage SQL! 🎉

- créer un fichier create_db.sql
- créer la base de donnée blog-dw si elle n'existe pas
- supprimer toutes les tables si elles existent
- créer une table pour chaque entité avec les colonnes correspondantes
  - ne pas oublier les clés étrangères !
