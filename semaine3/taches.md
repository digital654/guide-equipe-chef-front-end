# Répartition des tâches -- Projet Dashboard Admin

## Objectif

------------------------------------------------------------------------

# 1. DEKENI Toha  --- Layout & Navigation

Responsable de la **structure globale du dashboard**.

### À développer

-   Sidebar (menu gauche)  
-   Layout global du dashboard
-   Navigation entre les pages

### Composants

    components/navigation
       Sidebar.tsx
       Header.tsx

       
    dashboard/layout.tsx

### Page principale
    /dashboard

------------------------------------------------------------------------

# 2. Neon Genesis Evangelion  --- Carte Utilisateur

Responsable de l'affichage du **profil utilisateur principal**.

### À développer

-   Header 
-   Carte "Bonjour utilisateur"
-   Avatar
-   Informations membre
-   Bouton modifier profil

### Composants

    components/user-profil/
       UserCard.tsx
       ProfileInfo.tsx

------------------------------------------------------------------------

# 3. Wilfreed --- Statistiques

Responsable des **cartes statistiques du dashboard**.

### À développer

-   Documents envoyés
-   Statut du dossier
-   Cotisation
-   Notifications

### Composants

    components/document-stats/
       StatsCard.tsx
       StatsGrid.tsx

------------------------------------------------------------------------

# 4. Marc Emmanuel --- Gestion des documents

Responsable de toute la **gestion des documents**.

### À développer

-   Liste des documents
-   Upload de document
-   Modification
-   Téléchargement
-   Statut (validé / en révision)

### Composants

    components/documents/

       DocumentList.tsx
       DocumentItem.tsx
       UploadDocument.tsx

------------------------------------------------------------------------

# 5. Serge --- Profil & Paiement

Responsable de la **colonne droite du dashboard**.

### À développer

-   Complétion du profil
-   Barre de progression
-   Statut de cotisation
-   Téléchargement du reçu


### Composants

    components/profil/
       ProfileCompletion.tsx
       ProgressBar.tsx
       PaymentCard.tsx

------------------------------------------------------------------------

