# FacturationWebApp - Projet Technique pour Développeur Junior

## Introduction
Bienvenue dans ce test technique visant à évaluer vos compétences en développement Ruby on Rails. L'objectif est de créer une application de gestion de factures pour une entreprise. Cette application permettra à un utilisateur de s'authentifier, de créer des éléments à facturer, de composer des factures et devis, de gérer les différentes TVA applicables, ainsi que de gérer la liste des clients de l'entreprise.

## Fonctionnalités

### Authentification
En tant qu'utilisateur,
- Je dois pouvoir m'inscrire avec mon adresse e-mail et un mot de passe sécurisé.
- Je dois pouvoir me connecter avec mes identifiants.

### Gestion des données de l'entreprise
En tant qu'utilisateur,
- Je dois pouvoir saisir les informations de mon entreprise, telles que le nom, le numéro de SIRET, l'adresse, etc.
- Je dois pouvoir modifier ces informations si nécessaire.

### Gestion des clients
En tant qu'utilisateur,
- Je dois pouvoir ajouter un nouveau client avec des informations telles que le nom, l'adresse, l'email, etc.
- Je dois pouvoir visualiser la liste de tous les clients de l'entreprise.
- Je dois pouvoir modifier les informations d'un client existant.
- Je dois pouvoir supprimer un client de la liste.

### Éléments à facturer
En tant qu'utilisateur,
- Je dois pouvoir ajouter des produits ou des services avec leur nom, description et prix unitaire.
- Je dois pouvoir visualiser la liste de tous les produits et services disponibles.

### Création de devis
En tant qu'utilisateur,
- Je dois pouvoir créer un devis en sélectionnant des produits ou services à partir de la liste.
- Je dois pouvoir spécifier la quantité pour chaque produit ou service dans le devis.
- Je dois pouvoir associer un devis à un client existant.
- Je dois pouvoir visualiser un récapitulatif du devis avant de le valider.

### Validation de devis
En tant qu'utilisateur,
- Je dois pouvoir valider un devis pour le transformer en facture.
- Je dois recevoir une confirmation après la validation du devis.

### Composition de factures
En tant qu'utilisateur,
- Je dois pouvoir créer une facture en sélectionnant des produits ou services à partir de la liste.
- Je dois pouvoir spécifier la quantité pour chaque produit ou service dans la facture.
- Je dois pouvoir associer une facture à un client existant.
- Je dois pouvoir ajouter des notes ou des commentaires à la facture.

### Gestion des TVA
En tant qu'utilisateur,
- Je dois pouvoir définir les taux de TVA applicables à mes produits ou services.
- Je dois pouvoir sélectionner le taux de TVA approprié lors de la création de devis et de factures.
- Le montant total de la facture doit refléter correctement les taxes associées.

### Consultation des factures
En tant qu'utilisateur,
- Je dois pouvoir visualiser la liste de toutes mes factures.
- Je dois pouvoir consulter le détail d'une facture spécifique.

## Instructions pour le test
1. Clonez ce dépôt.
2. Créez une nouvelle branche pour votre travail.
3. Développez l'application en utilisant Ruby on Rails.
4. Assurez-vous de suivre les meilleures pratiques de codage et d'organisation du projet.
5. Utilisez des migrations pour la création de la base de données.
6. Ajoutez des tests pour les fonctionnalités clés.
7. Assurez-vous que l'application est fonctionnelle et respecte les fonctionnalités spécifiées.
8. Mettez à jour ce fichier README avec des instructions détaillées pour exécuter l'application localement.

Bonne chance ! Si vous avez des questions, n'hésitez pas à les poser.
