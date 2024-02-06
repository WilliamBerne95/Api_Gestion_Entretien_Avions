# Api_Gestion_Entretien_Avions

## Description

Dans le contexte de la gestion du système d'information de la base aérienne d'Istres, le projet vise à créer une application de gestion des aéronefs. L'API, élaborée en NodeJS et TypeScript, sera connectée à une base de données MariaDB pour assurer la gestion complète des données.
## Modèle conceptuel

![Modele conceptuel](https://github.com/WilliamBerne95/Api_Gestion_Entretien_Avions/assets/110680560/b2fba41b-6012-4cc5-887f-8fc727ad6e82)

## Liste des Endpoints

| Méthode HTTP | Endpoint                    | Description                                       |
|--------------|-----------------------------|---------------------------------------------------|
| GET          | /avions                     | Récupère la liste de tous les avions.             |
| GET          | /avions/{id}                | Récupère les détails d'un avion spécifique.       |
| POST         | /avions                     | Crée un nouvel avion.                             |
| PUT          | /avions/{id}                | Met à jour les détails d'un avion existant.       |
| DELETE       | /avions/{id}                | Supprime un avion spécifique.                     |
| GET          | /entretiens                 | Récupère la liste de tous les entretiens.         |
| GET          | /entretiens/{id}            | Récupère les détails d'un entretien spécifique.   |
| POST         | /entretiens                 | Crée un nouvel entretien.                         |
| PUT          | /entretiens/{id}            | Met à jour les détails d'un entretien existant.   |
| DELETE       | /entretiens/{id}            | Supprime un entretien spécifique.                 |
| GET          | /mecaniciens                | Récupère la liste de tous les mécaniciens.       |
| GET          | /mecaniciens/{id}           | Récupère les détails d'un mécanicien spécifique. |
| POST         | /mecaniciens                | Crée un nouveau mécanicien.                      |
| PUT          | /mecaniciens/{id}           | Met à jour les détails d'un mécanicien existant. |
| DELETE       | /mecaniciens/{id}           | Supprime un mécanicien spécifique.               |
