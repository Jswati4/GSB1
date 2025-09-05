# GSB1 - Application de Gestion des Visites Médicales

*🇫🇷 Version Française*

### 📖 Contexte

Cette application aide les **visiteurs médicaux** à gérer leurs activités :

* Rédiger et modifier des **rapports de visite** (date, médecin, médicaments présentés, échantillons offerts, bilan).
* Consulter et mettre à jour les **informations sur les médecins** (coordonnées, spécialité, historique des visites).
* Accéder à la **base de produits** (médicaments, composition, posologie, interactions).

L’architecture utilisée est **MVC (Modèle – Vue – Contrôleur)** afin de séparer :

* le stockage et la gestion des données (**Modèle**),
* l’interface utilisateur (**Vue**),
* la logique de navigation (**Contrôleur**).

### 🏗️ Organisation du projet

/projet
│── /modeles         → classes métiers (Médecin, Rapport, Produit…)
│── /vues            → pages et formulaires affichés à l’utilisateur
│── /controleurs     → gestion des actions utilisateur
│── /config          → paramètres (connexion BD…)
│── index.php        → point d’entrée du site
│── README.md        → documentation du projet

### ⚙️ Fonctionnalités principales

* **Rapports de visite** : création, modification, consultation.
* **Médecins** : recherche, fiche détaillée, historique, modification.
* **Produits** : informations sur les médicaments (composition, posologie, contre-indications, interactions).


### 🚀 Installation

1. Cloner le projet :

   ```bash
   git clone https://github.com/mon-projet/visites-medicales.git
   cd visites-medicales
   ```
2. Importer la base de données depuis `database.sql`.
3. Modifier la configuration dans `/config/db.php`.
4. Lancer un serveur local (Apache/Nginx + PHP).
5. Accéder au site via :

   ```
   http://localhost:8080/Projet%20GSB/
   ```
## GSB1 - Medical Visit Management Application
 *🇬🇧 English Version*

### 📖 Context

This application helps **medical representatives** manage their daily activities:

* Create and edit **visit reports** (date, doctor, products presented, samples offered, feedback).
* View and update **doctor information** (contact details, specialty, visit history).
* Access the **product database** (drugs, composition, dosage, interactions).

The system is built using **MVC architecture (Model – View – Controller)** to clearly separate:

* data management (**Model**),
* user interface (**View**),
* application logic (**Controller**).

### 🏗️ Project Structure

/project
│── /models          → business classes (Doctor, Report, Product…)
│── /views           → user interface (pages, forms, lists)
│── /controllers     → handles user actions
│── /config          → settings (database connection…)
│── index.php        → main entry point
│── README.md        → project documentation
```

### ⚙️ Main Features

* **Visit Reports**: create, edit, view.
* **Doctors**: search, detailed profile, history, update information.
* **Products**: drug information (composition, dosage, contraindications, interactions).

### 🚀 Installation

1. Clone the project:

   ```bash
   git clone https://github.com/my-project/medical-visits.git
   cd medical-visits
   ```
2. Import the database from `database.sql`.
3. Update the configuration in `/config/db.php`.
4. Start a local server (Apache/Nginx + PHP).
5. Open the site in your browser:

   ```
   http://localhost:8080/Projet%20GSB/
   ```
