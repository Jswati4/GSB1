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

| Dossier / Fichier | Description                                                     |
| ----------------- | --------------------------------------------------------------- |
| `/modeles`        | Contient les **classes métiers** (Médecin, Rapport, Produit…)   |
| `/vues`           | Regroupe les **pages et formulaires** affichés à l’utilisateur  |
| `/controleurs`    | Gère les **actions de l’utilisateur** et la logique métier      |
| `/config`         | Fichiers de **configuration** (connexion à la base de données…) |
| `index.php`       | Point d’entrée principal de l’application                       |
| `README.md`       | Documentation du projet                                         |


### ⚙️ Fonctionnalités principales

* **Rapports de visite** : création, modification, consultation.
* **Médecins** : recherche, fiche détaillée, historique, modification.
* **Produits** : informations sur les médicaments (composition, posologie, contre-indications, interactions).


### 🚀 Installation

1. Cloner le projet :

   ```bash
   https://github.com/Jswati4/GSB1.git
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

| Folder / File  | Description                                              |
| -------------- | -------------------------------------------------------- |
| `/models`      | Contains **business classes** (Doctor, Report, Product…) |
| `/views`       | Contains **pages and forms** displayed to the user       |
| `/controllers` | Manages **user actions** and business logic              |
| `/config`      | **Configuration files** (database connection, settings…) |
| `index.php`    | Main entry point of the application                      |
| `README.md`    | Project documentation                                    |

```

### ⚙️ Main Features

* **Visit Reports**: create, edit, view.
* **Doctors**: search, detailed profile, history, update information.
* **Products**: drug information (composition, dosage, contraindications, interactions).

### 🚀 Installation

1. Clone the project:

   ```bash
   https://github.com/Jswati4/GSB1.git
   cd medical-visits
   ```
2. Import the database from `database.sql`.
3. Update the configuration in `/config/db.php`.
4. Start a local server (Apache/Nginx + PHP).
5. Open the site in your browser:

   ```
   http://localhost:8080/Projet%20GSB/
   ```
