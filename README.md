# 🛍️ Gestion des Produits - Application Laravel

Une application Laravel simple permettant de gérer les utilisateurs (inscription, connexion, déconnexion) et les produits (ajout, modification, suppression, consultation).

---

## 🚀 Fonctionnalités

### ✅ Authentification Utilisateur
- Inscription avec validation des champs
- Connexion sécurisée
- Déconnexion

### 🗂️ Gestion des Produits (CRUD)
- Ajouter un produit
- Voir la liste des produits
- Modifier un produit
- Supprimer un produit
- Afficher les détails d’un produit

---

## 🛠️ Technologies utilisées

- [Laravel 10](https://laravel.com/)
- PHP 8.x
- MySQL 
- Frontend Vue Js

---

## ⚙️ Installation

# 1. Cloner le projet
git clone https://github.com/ton-utilisateur/gestion-produits.git
cd gestion-produits

# 2. Installer les dépendances PHP via Composer
composer install

# 3. Copier le fichier .env exemple
cp .env.example .env

# 4. Générer la clé de l'application
php artisan key:generate

# 5. Configurer la base de données dans le fichier .env
# (Modifie DB_DATABASE, DB_USERNAME, DB_PASSWORD selon ta config)

# 6. Exécuter les migrations pour créer les tables
php artisan migrate

# (Optionnel) 7. Exécuter les seeders si tu en as
php artisan db:seed

# 8. Démarrer le serveur de développement Laravel
php artisan serve



