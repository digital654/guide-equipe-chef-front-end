# 🚀 Projet Next.js - Organisation & Méthodologie de Travail

## 📌 Objectif

Ce projet est développé avec **Next.js** pour créer une application web moderne, performante et bien structurée.

Nous allons travailler en équipe avec une organisation claire et une gestion propre du code via GitHub.

## 🧱 Structure du projet

```txt
/
├── app
├── components
├── lib
├── styles
└── public
```

## 📂 Dossier `app/` (Pages & Routes)

C'est le dossier principal de l'application (App Router). Chaque dossier représente une route du site.

### Exemple

```txt
app/
├── page.tsx
├── layout.tsx
├── about/
│   └── page.tsx
└── contact/
    └── page.tsx
```

### Explication

- `page.tsx` : page principale (`/`)
- `about/page.tsx` : route `/about`
- `contact/page.tsx` : route `/contact`
- `layout.tsx` : structure globale (Navbar, Footer, etc.)

👉 Chaque membre peut être responsable d'une page spécifique.

## 🧩 Dossier `components/` (Composants réutilisables)

Contient les composants utilisés dans plusieurs pages.

### Exemple

```txt
components/
├── Navbar.tsx
├── Footer.tsx
├── Card.tsx
└── Button.tsx
```

### Important : Organisation des composants par page

Pour mieux organiser le code, chaque page doit avoir un dossier de composants dédié.

- On crée un composant principal de page.
- Puis on crée les composants de sections dans ce même dossier.
- Ensuite, on importe ces sections dans la page (`page.tsx`).

Exemple :

```txt
components/
└── page-accueil/
    ├── accueil-main.tsx
    ├── section-hero.tsx
    └── section-apropos.tsx
```

⚠️ Règle importante : si un composant est utilisé dans plusieurs pages, il doit rester dans `components/` (exemple : bouton, card, navbar).

## 🛠 Dossier `lib/` (Logique & Fonctions)

Contient :

- fonctions utilitaires
- configuration API
- connexion base de données
- helpers

### Exemple

```txt
lib/
├── db.ts
├── api.ts
└── utils.ts
```

## 🎨 Dossier `styles/` (Styles globaux)

Contient :

- CSS global

### Exemple

```txt
styles/
└── globals.css
```

## 🖼 Dossier `public/` (Fichiers statiques)

Contient :

- images
- logos
- icônes
- PDF

### Exemple

```txt
public/
├── logo.png
└── images/
```

Accessible via :

```txt
/logo.png
```

## 👥 Organisation du travail en équipe

### 🔀 Gestion des branches

Chaque membre doit :

1. Cloner le projet.
2. Créer une branche.
3. Faire ses modifications.
4. Push la branche sur GitHub.
5. Créer une Pull Request.

Commande :

```bash
git checkout -b feature/nom-de-la-fonctionnalite
```

Exemples :

```txt
feature/homepage
feature/contact-form
feature/dashboard
```

### 📌 Règles importantes

- ❌ Ne jamais travailler directement sur `main`
- ✅ Une fonctionnalité = une branche
- ✅ Nom clair pour les branches
- ✅ Code propre et organisé
- ✅ Composants réutilisables

### 📄 Répartition des tâches

1. Chef d'équipe / Lead  
  Coordination, qualité, conventions, review et intégration finale.  
  Tu aides l'équipe, tu corriges et tu merges les Pull Requests.

2.  Membre 1 - Header + Hero  
  Navbar (menu, logo, bouton), Hero section et responsive mobile du header.

3.  Membre 2 - Présentation / À propos  
  Bloc présentation, statistiques, CTA, mise en page image + texte.

4. Membre 3 - Événements + Sponsors  
  Section événements, cartes événements, sponsors et slider si nécessaire.

5. Membre 4 - Témoignages + FAQ + News + Footer  
  Avis clients, FAQ, dernières nouvelles et footer.

### 🔄 Collaboration

- Communication via groupe
- Pull Requests obligatoires
- Review avant merge
- Respect de la structure du projet

## ⚙️ Commandes utiles

Installer les dépendances :

```bash
npm install
```

Lancer le projet :

```bash
npm run dev
```

Build production :

```bash
npm run build
```

## 🎯 Objectif final

- code propre
- structure organisée
- travail collaboratif efficace
- projet professionnel
