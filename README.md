# EdifisPro

EdifisPro est une application Symfony dédiée à la gestion des chantiers. Ce projet permet d'organiser et de gérer efficacement les chantiers, les employés ainsi que leurs affectations aux différents projets.

## 📌 Description
L'application offre un espace dédié aux administrateurs pour gérer les employés, et un espace utilisateur permettant aux employés de consulter les informations relatives à leurs chantiers.

## 🚀 Fonctionnalités principales
- **Authentification** : Connexion et inscription pour les utilisateurs et les administrateurs.
- **Gestion des utilisateurs** : Ajout, modification, suppression des utilisateurs par un administrateur.
- **Gestion des chantiers** : Création, modification, suppression de chantiers.
- **Affectation des employés** : Attribution des employés aux différents chantiers.
- **Tableau de bord** : Interface personnalisée pour chaque type d'utilisateur (administrateur, employé).

## 📂 Structure du projet
```
.
├── config/           # Configuration de l'application Symfony
├── migrations/       # Fichiers de migration de la base de données
├── public/           # Dossier public contenant l'index.php
├── src/              # Code source de l'application (Controllers, Entities, Repositories)
├── templates/        # Vues Twig pour l'affichage
├── .env              # Configuration de l'environnement
├── composer.json     # Dépendances PHP
├── README.md         # Documentation du projet
```

## 🔧 Prérequis
- PHP >= 8.0
- Composer
- Symfony CLI
- MariaDB ou MySQL

## 📥 Installation
1. Clonez ce dépôt :
```bash
$ git clone https://github.com/Lcs-93/EdifisPro.git
```
2. Rendez-vous dans le répertoire cloné :
```bash
$ cd EdifisPro
```
3. Installez les dépendances PHP avec Composer :
```bash
$ composer install
```
4. Configurez votre base de données dans le fichier `.env` :
```
DATABASE_URL="mysql://root:@127.0.0.1:3306/edifispro?serverVersion=10.4.32-MariaDB&charset=utf8mb4"
```
5. Effectuez les migrations :
```bash
$ php bin/console doctrine:migrations:migrate
```
6. Lancez le serveur Symfony :
```bash
$ symfony server:start
```

## 📌 Utilisation
Accédez à l'application via votre navigateur à l'adresse suivante :
```
http://127.0.0.1:8000
```

## 🛠️ Technologies utilisées
- **Symfony** (PHP framework)
- **Twig** (Moteur de templates)
- **MariaDB / MySQL** (Base de données)
- **HTML / CSS / JavaScript** (Frontend)

## 📄 Licence
Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 📣 Auteur
Projet créé par **Lcs-93**. N'hésitez pas à me contacter pour toute suggestion ou amélioration !

---

🔥 Bon développement !

