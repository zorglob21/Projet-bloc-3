# Projet-bloc-3
application Django pour un site catalogue, avec fonction d'administration.
Les admins peuvent ajouter / modifier / supprimer des produits, mettre un produit en promotion, ajouter d'autres adminds et limiter leurs droits...

Les tailles et catégories sont également modifiables, et l'affichage de ces données est dynamique dans le menu de filtre.

![alt text](https://res.cloudinary.com/dr3sekypo/image/upload/v1684244469/Screenshot_2023-05-16_153339_yqqiae.jpg)

Pour faire fonctionner l'application sur le serveur local, il faut créer un fichier .env à la racine du projet et reseigner les variables suivantes:

DATABASE_URL=

SECRET_KEY=

api_key=

cloud_name=

api_secret=

puis dans settings.py:

Soit configurer DEBUG = True pour activer les informations de débuggage et simuler un environnement de développement 

ou modifier  ALLOWED_HOSTS= et commenter  SECURE_SSL_REDIRECT pour autoriser les connections http.
