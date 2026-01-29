# Portfolio – Alexandre Berrel

Ce dépôt contient le code source de mon portfolio de développeur web.  
Il présente mon travail, mes projets et les interfaces que je conçois au quotidien.

---

## 🧩 Aperçu du projet

Le site est structuré autour de plusieurs sections :

### • Navigation
Une barre de navigation fixe, pensée pour rester lisible et accessible sur toutes les tailles d’écran.

### • Hero section
Présentation rapide, deux boutons d’appel à l’action et un effet ripple pour rendre les interactions plus vivantes.

### • Section projets
Aperçu de mes réalisations avec un bouton personnalisé utilisant un effet de “jauge” animé.  
L’objectif est d’apporter une touche visuelle plus marquée tout en gardant une interface propre.

---

## 🛠️ Stack technique

- **HTML5** pour une structure claire et sémantique  
- **SCSS** pour une organisation modulaire et des animations maîtrisées  
- **JavaScript** (léger, uniquement pour les interactions nécessaires)  
- **Font Awesome** pour les icônes  
- **GitHub Pages** pour l’hébergement

---

## 🎨 Points d’attention sur l’UI

- Animations douces basées sur `transform` et `opacity` pour de bonnes performances  
- Effet ripple sur les boutons de la hero  
- Bouton “Voir tous mes projets” entièrement custom :  
  - fond transparent au repos  
  - gradient animé qui remplit partiellement le bouton  
  - légère courbure sur le bord droit  
  - icône qui tourne au survol  
- Mise en page responsive pensée mobile-first

---

## 📁 Structure du projet

/
├── index.html
├── /assets
│   ├── /images
│   └── /icons
├── /styles
│   ├── main.scss
│   ├── /components
│   ├── /sections
│   └── /utils
└── README.md

Code

---

## 🚀 Installation

Clone du projet :

```bash
git clone https://github.com/<ton-pseudo>/<nom-du-repo>.git
Lancement du projet :

Ouvrir index.html dans le navigateur ou utiliser une extension type Live Server.

🌍 Déploiement
Le site est déployé via GitHub Pages.
Pour mettre à jour la version en ligne :

bash
git add .
git commit -m "Mise à jour du portfolio"
git push


📬 Contact
Alexandre Berrel  
Développeur Web
