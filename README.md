# 🍽️ OhMyFood - Projet de Développement Frontend

## 📋 Présentation du Projet

**OhMyFood** est une application web innovante développée pour une startup en pleine expansion dans le secteur de la restauration gastronomique. Le projet consiste à créer un site **mobile-first** permettant aux clients de consulter les menus de restaurants partenaires et de composer leur repas en avance.

### 🎯 Objectif Principal

Développer une plateforme complète répertoriant les menus de 4 restaurants gastronomiques parisiens, offrant une expérience utilisateur enrichie grâce à des animations CSS sophistiquées.

---

## 🚀 Fonctionnalités

- 📱 **Design Mobile-First** : Interface optimisée en priorité pour mobile, puis adaptée pour tablette et desktop
- ✨ **Animations CSS Avancées** : Transitions et animations fluides pour enrichir l'expérience utilisateur
- 📍 **4 Menus de Restaurants** : Pages dédiées à chaque restaurant partenaire
- 🎨 **Design Cohérent** : Système de design unifié sur toutes les pages
- 🔄 **Navigation Intuitive** : Structure claire et facile à naviguer
- 📊 **Responsive Design** : Adaptation parfaite sur tous les appareils

---

## 🎓 Compétences Développées

Ce projet a permis de maîtriser les compétences suivantes :

### Frontend

- ✅ Intégration **HTML/CSS** conforme aux standards W3C
- ✅ **CSS Avancé** avec animations fluides et transitions
- ✅ Approche **Mobile-First**
- ✅ **Design Responsive** avec media queries

### Outils et Bonnes Pratiques

- ✅ Préprocesseur **SASS** pour une organisation optimale du CSS
- ✅ **Git et GitHub** pour la gestion de version
- ✅ **GitHub Pages** pour le déploiement et l'hébergement

### Compétences Métier

- ✅ Mise en œuvre d'effets CSS graphiques avancés
- ✅ Assurance de la cohérence graphique
- ✅ Mise en place d'une structure de navigation
- ✅ Configuration d'un environnement front-end professionnel

---

## 🏗️ Structure du Projet

```text
Ohmyfood/
├── index.html                  # Page d'accueil
├── README.md                   # Documentation du projet
├── assets/
│   ├── CSS/
│   │   ├── main.css           # Fichier CSS compilé
│   │   └── main.min.css       # Fichier CSS minifié
│   ├── img/                   # Dossier des images
│   │   ├── logo/              # Logos du site
│   │   └── restaurants/       # Images des restaurants
│   └── SASS/
│       ├── main.scss          # Fichier SASS principal
│       ├── abstracts/         # Variables et mixins
│       │   ├── _mixins.scss
│       │   └── _variables.scss
│       ├── base/              # Styles de base
│       │   ├── _normalize.scss
│       │   ├── _reset.scss
│       │   └── _typography.scss
│       ├── components/        # Composants réutilisables
│       │   ├── _buttons.scss
│       │   ├── _footer.scss
│       │   ├── _header.scss
│       │   ├── _heart.scss
│       │   └── _loader.scss
│       ├── layouts/           # Mises en page
│       │   └── _main-content.scss
│       └── pages/             # Styles spécifiques aux pages
│           ├── _home.scss
│           └── _restaurant.scss
└── restaurants/               # Pages des restaurants
    ├── a_la_francaise.html
    ├── la_note_enchantee.html
    ├── la_palette_du_gout.html
    └── le_delice_des_sens.html
```

---

## 🎨 Architecture SASS

Le projet utilise une architecture SASS modulaire et maintenable :

- **abstracts/** : Variables de couleurs, breakpoints et mixins réutilisables
- **base/** : Styles normalisés et typographie
- **components/** : Styles des composants individuels (boutons, header, footer, etc.)
- **layouts/** : Mises en page générales
- **pages/** : Styles spécifiques à chaque type de page

Cette organisation facilite la maintenance et l'évolutivité du code.

---

## 📱 Responsive Design

Le site est optimisé pour les trois principaux breakpoints :

- 📱 **Mobile** : < 768px
- 📊 **Tablette** : 768px - 1024px
- 🖥️ **Desktop** : > 1024px

Approche **Mobile-First** : le CSS principal concerne le mobile, les media queries ajoutent les règles pour les appareils plus grands.

---

## ✨ Animations CSS

Le projet intègre des animations CSS sophistiquées pour enrichir l'UX :

- **Animations de survol** sur les éléments interactifs
- **Transitions fluides** lors de la navigation
- **Animations de chargement** pour le feedback utilisateur
- **Effets d'apparition** des contenus

Toutes les animations respectent les principes d'UX en offrant l'animation inverse lors du départ du survol.

---

## 🔗 Pages du Site

### Page d'Accueil (`index.html`)

Page principale présentant :

- Header avec logo
- Section de localisation
- Section "Explorez le restaurant"
- Liste des 4 restaurants avec images et descriptions
- Footer avec informations de contact

### Pages Restaurant

Chaque restaurant dispose d'une page dédiée présentant :

- Bannière avec image du restaurant
- Nom du restaurant et bouton favoris
- Menu organisé par catégories
- Plats avec descriptions et prix
- Bouton de commande

**Restaurants partenaires :**

1. À la française
2. La note enchantée
3. La palette du goût
4. Le délice des sens

---

## 🛠️ Technologies Utilisées

| Technologie | Usage |
|-------------|-------|
| **HTML5** | Structure sémantique du site |
| **CSS3** | Styles et animations |
| **SASS** | Préprocesseur CSS |
| **Git** | Gestion de version |
| **GitHub** | Hébergement du code |
| **GitHub Pages** | Déploiement et hosting |

---

## ✅ Validation et Qualité

Le projet respecte les standards web :

- ✓ Code HTML validé au **W3C**
- ✓ Code CSS validé au **W3C**
- ✓ Respect des bonnes pratiques d'accessibilité
- ✓ Performance optimisée
- ✓ Tests sur tous les appareils et navigateurs modernes

---

## 🚀 Déploiement

Le site est déployé en live sur **GitHub Pages** et accessible en ligne.

[Voir le site en ligne](https://weavyx.github.io/Ohmyfood/)

---

## 📚 Points Clés du Développement

### Approche Mobile-First

- Conception d'abord pour les petits écrans
- Utilisation de media queries pour l'agrandissement
- Meilleure performance et UX sur mobile

### Animations CSS

- Utilisation exclusive de CSS (pas de JavaScript)
- Transitions fluides et naturelles
- Animations inversées au départ du survol

### Structure SASS Modulaire

- Séparation des concerns
- Variables centralisées pour les couleurs et valeurs
- Mixins réutilisables pour les media queries
- Code DRY (Don't Repeat Yourself)

### Gestion de Version

- Commits réguliers et descriptifs
- Historique clair du développement
- Repository public pour la collaboration

---

## 💡 Concepts Avancés Intégrés

- **Préprocessing CSS** avec SASS
- **Design Responsive** avec breakpoints standards
- **Animations CSS modernes** pour l'UX
- **Gestion de projet** avec Git et GitHub
- **Contrôle de qualité** avec validation W3C

---

## 📝 Remarques pour l'Évolution Future

Pour des évolutions futures, notamment l'intégration de JavaScript, il serait pertinent de :

- Envisager des animations plus complexes avec JavaScript (timing, séquençage)
- Implémenter une logique métier pour la gestion des commandes
- Ajouter des interactions utilisateur avancées
- Optimiser les performances avec animations GPU-accélérées

---

## 🎯 Conclusion

Ce projet représente une implémentation complète d'une interface web moderne suivant les meilleures pratiques du développement frontend. Il démontre la capacité à créer des sites responsifs, animés et maintenables, tout en utilisant les outils professionnels de gestion de version.

Les compétences développées lors de ce projet sont directement applicables aux projets web contemporains et essentielles pour un développeur front-end polyvalent.

---

## 👤 Auteur

**Développeur** : Weavyx (Maxime Nardelli)
**Projet** : OhMyFood - Startup de Restauration
**Durée** : 70 heures
**Date** : 2025

---

## 📄 Licence

Ce projet fait partie d'un parcours de formation et reste la propriété intellectuelle du développeur.

---

**Merci de consulter ce README pour mieux comprendre la structure et les objectifs du projet !** 🚀
