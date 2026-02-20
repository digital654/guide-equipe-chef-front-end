# Répartition des Tâches – Dictionnaire de Données

**Projet :** Création du dictionnaire de données basé sur les User Stories  
**Document source :** User Stories (22 pages)  
**Deadline :** Vendredi 22h00  
**Supervisé par :** Chef Back-front  

---

## Instruction importante

Vous devez vous baser uniquement sur les **User Stories (22 pages)** pour identifier les données nécessaires.

Comme le document contient 22 pages, on divise les pages entre les membres.  
Chaque membre analyse sa partie pour identifier :

- Les entités (tables)
- Les champs nécessaires
- Les types de données
- Les contraintes principales

---

## Répartition

### 🔹 Membre 1  
Analyse des pages 1 à 6  

### 🔹 Membre 2  
Analyse des pages 7 à 12  

### 🔹 Membre 3  
Analyse des pages 13 à 17  

### 🔹 Membre 4  
Analyse des pages 18 à 22  
---

## 📘 Modèle Simple de Dictionnaire de Données (Exemple)

### Table : `utilisateur`

| Nom du champ   | Type     | Taille | Contraintes                     | Description                              |
|----------------|----------|--------|----------------------------------|------------------------------------------|
| id_user        | INT      | 11     | PRIMARY KEY, AUTO_INCREMENT      | Identifiant unique de l’utilisateur      |
| nom            | VARCHAR  | 100    | NOT NULL                         | Nom complet de l’utilisateur             |
| email          | VARCHAR  | 150    | UNIQUE, NOT NULL                 | Adresse email                            |
| mot_de_passe   | VARCHAR  | 255    | NOT NULL                         | Mot de passe crypté                      |
| date_creation  | DATETIME | —      | DEFAULT CURRENT_TIMESTAMP        | Date de création du compte               |

---

## Objectif final

À la fin, on doit avoir :

- Un dictionnaire simple  
- Basé uniquement sur les User Stories  
- Clair et organisé  
- Regroupé dans un seul document  

---

Je suis à votre disposition pour les questions.