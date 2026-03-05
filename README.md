# 🎓 Système de Gestion des Étudiants – LAB8

![PHP](https://img.shields.io/badge/PHP-8.x-blue)
![Architecture](https://img.shields.io/badge/Architecture-MVC-green)
![Security](https://img.shields.io/badge/Security-Protection%20CSRF-red)
![Status](https://img.shields.io/badge/Status-Projet%20Académique-orange)
![License](https://img.shields.io/badge/License-Éducatif-lightgrey)

---

## 📌 Présentation

Ce projet est une **application web de gestion des étudiants** développée en **PHP** en utilisant une **architecture MVC personnalisée**.

Elle permet de gérer les étudiants et les filières de manière sécurisée, avec un système d’authentification et des routes protégées.

---

## ✨ Fonctionnalités

- 🔐 Authentification sécurisée (Connexion / Déconnexion)
- 👨‍🎓 Gestion des étudiants (CRUD : Créer, Lire, Modifier, Supprimer)
- 🏫 Gestion des filières
- 🛡️ Protection contre les attaques CSRF
- 🔎 Validation et nettoyage des données
- 🧭 Routeur personnalisé
- 🗃️ Utilisation du pattern DAO pour l’accès à la base de données
- 📝 Système de journalisation (Logs)

---

## 🏗️ Architecture du projet

```
lab8/
│
├── public/              # Point d'entrée de l'application (index.php)
├── src/
│   ├── Container/       # Fabrique de l'application
│   ├── Controller/      # Contrôleurs MVC
│   ├── Core/            # Router, Request, Response, View
│   ├── Dao/             # Couche d'accès à la base de données
│   └── Security/        # Authentification et sécurité
│
├── views/               # Vues PHP
├── logs/                # Fichiers de journalisation
└── docs/                # Documentation
```

---

## ⚙️ Technologies utilisées

- PHP (Programmation Orientée Objet)
- MySQL
- Architecture MVC
- Pattern DAO
- HTML / CSS
- Bonnes pratiques de sécurité web

---

## 🚀 Guide d’installation

### 1️⃣ Cloner le dépôt

```bash
git clone https://github.com/your-username/lab8.git
```

### 2️⃣ Configuration de la base de données

- Créer une base de données MySQL
- Modifier les informations de connexion dans :

```
src/Dao/DBConnection.php
```

### 3️⃣ Lancer l’application

- Placer le projet dans `htdocs` (XAMPP)  
  ou  
- Configurer un Virtual Host

Accéder à l’application via :

```
http://localhost/lab8/public
```

---

## 🔐 Sécurité implémentée

Le système inclut :

- Protection par token CSRF
- Validation des entrées utilisateur
- Nettoyage des données
- Middleware d’authentification
- Système de journalisation

---

## 👨‍💻 Composants principaux

### 🔄 Routeur

Le routeur gère :

- l’analyse des URL
- la redirection vers les contrôleurs
- l’exécution des méthodes correspondantes

### 🗄️ Couche DAO

Cette couche encapsule les opérations SQL :

- `EtudiantDao.php`
- `FiliereDao.php`
- `AdminDao.php`

---

## 📌 Améliorations futures

- Gestion des rôles utilisateurs
- Intégration d’une API REST
- Amélioration de l’interface avec Bootstrap
- Mise en place de tests unitaires

---

## 🧑‍🎓 Auteur

Ait Hmad Oussama
---



---

## 🎥 Vidéo de démonstration montrant la réussite du test

https://github.com/user-attachments/assets/4ea46a31-de86-4527-bdcb-3bde47659364
