# 🍽️ OhMyFood - Projet de Développement Frontend

## 📋 Présentation du Projet

**OhMyFood** est une application web innovante développée pour une startup en pleine expansion dans le secteur de la restauration gastronomique. Le projet consiste à créer un site **mobile-first** permettant aux clients de consulter les menus de restaurants partenaires et de composer leur repas en avance.

> **Type de projet** : Challenge de formation | **Statut** : ✅ Complété | **Durée** : ~70 heures

### 🎯 Objectifs Principaux

- ✅ Développer une plateforme répertoriant les menus de 4 restaurants gastronomiques parisiens
- ✅ Implémenter un design **mobile-first** responsive sur tous les appareils
- ✅ Créer des animations CSS sophistiquées pour enrichir l'UX
- ✅ Respecter les standards web et bonnes pratiques front-end
- ✅ Organiser le code CSS avec SASS en architecture modulaire

### 🔗 Accès Rapide

- 🌐 **[Site en ligne](https://weavyx.github.io/Ohmyfood/)**
- 💻 **[Code Source - GitHub](https://github.com/Weavyx/Ohmyfood)**

---

## 🚀 Fonctionnalités

- 📱 **Design Mobile-First** : CSS optimisé prioritairement pour mobile, adaptation progressive
- ✨ **Animations CSS Avancées** : Transitions fluides sans JavaScript (keyframes, transforms)
- 📍 **4 Menus de Restaurants** : Pages dédiées avec menus complets par catégorie
- 🎨 **Design Cohérent** : Système visuel unifié sur toutes les pages
- 🔄 **Navigation Intuitive** : Structure claire et ergonomique
- ❤️ **Fonction Favoris** : Cœur animé avec feedback utilisateur
- ⚡ **Performance Optimale** : CSS minifié, images optimisées, 60fps

---

## ✅ Livrables et Respect des Critères

| Critère | Statut | Détails |
|---------|--------|---------|
| Design Mobile-First | ✅ | CSS adapté et media queries pour tablette/desktop |
| Animations CSS | ✅ | Transitions fluides, animations de survol et chargement |
| 4 Restaurants | ✅ | Pages dédiées avec menus complets |
| Responsive Design | ✅ | Tests sur mobile, tablette et desktop |
| Code HTML/CSS validé | ✅ | Conforme aux standards W3C |
| Architecture SASS | ✅ | Structure modulaire et maintenable |
| Déploiement | ✅ | Accessible en live sur GitHub Pages |

---

## 🎓 Compétences Développées

### 🎨 Frontend & CSS Avancé

- ✅ **HTML5 sémantique** conforme W3C
- ✅ **CSS3 Avancé** : @keyframes, transitions, transforms GPU-accélérées
- ✅ **Approche Mobile-First** : conception progressive et performante
- ✅ **Design Responsive** : media queries fluides (768px, 1024px)

### 🔧 Outils et Méthodologies

- ✅ **Préprocesseur SASS** : architecture modulaire 7-in-1
  - Variables centralisées (`_variables.scss`)
  - Mixins réutilisables pour responsive (`_mixins.scss`)
  - Nesting et organisation logique
- ✅ **Gestion de version Git** : commits descriptifs et historique clair
- ✅ **Déploiement & Hosting** : GitHub Pages pour la mise en ligne
- ✅ **Code Minification** : CSS minifié pour performance

### 💼 Compétences Métier

- ✅ Mise en œuvre d'**effets CSS graphiques sophistiqués**
- ✅ **Assurance de la cohérence UX** sur tous les appareils
- ✅ Conception d'une **architecture CSS maintenable**
- ✅ Respect des **bonnes pratiques d'accessibilité**
- ✅ Configuration d'un **environnement front-end professionnel**

---

## 🏗️ Structure du Projet & Architecture SASS

Le projet utilise une **architecture SASS modulaire 7-in-1** pour scalabilité et maintenabilité :

```text
Ohmyfood/
├── index.html
├── assets/
│   ├── CSS/
│   │   ├── main.css          # CSS compilé
│   │   └── main.min.css      # CSS minifié
│   ├── img/                  # Images et logos
│   └── SASS/                 # Architecture modulaire
│       ├── abstracts/        # Variables, mixins
│       ├── base/             # Normalisation, typographie
│       ├── components/       # Boutons, header, footer, etc.
│       ├── layouts/          # Mises en page macro
│       └── pages/            # Styles spécifiques
└── restaurants/              # Pages des 4 restaurants
```

**Avantages** : Code DRY, facile à localiser/modifier, simple d'étendre, un seul fichier CSS compilé

---

## ✨ Animations CSS & Responsive Design

### 🎬 Animations CSS Implémentées

Le projet intègre des animations **sophistiquées et performantes** (CSS pur, sans JavaScript) :

| Animation | Type | Utilisation | Technique |
|-----------|------|-------------|-----------|
| **Survol boutons** | `transition` | Couleur/ombre | `hover`, `transform: scale()` |
| **Cœur animé** | `animation` | Ajout favoris | `@keyframes`, `animation-duration` |
| **Loader** | `animation` | Chargement | Rotation fluide `transform` |
| **Apparition contenu** | `animation` | Menu | `opacity`, `animation-delay` |

**Points clés** : GPU-accélérées (60fps), animations inversées, respect de `prefers-reduced-motion`, zéro dépendance

### 📱 Responsive Design (Mobile-First)

Le site s'adapte aux **3 breakpoints** avec approche progressive :

- 📱 **Mobile** : 320px - 768px (styles de base optimisés)
- 📊 **Tablette** : 768px - 1024px (ajout de media queries)
- 🖥️ **Desktop** : 1024px+ (layouts larges)

**Bénéfices** : Performance maximisée, meilleure UX mobile, CSS réduit

---

## 🔗 Pages et Contenu du Site

### 📄 Page d'Accueil (`index.html`)

Page principale servant de **point d'entrée** du site :

- ✅ Header avec logo OhMyFood
- ✅ Section de localisation (géolocalisation)
- ✅ Section de présentation "Explorez le restaurant"
- ✅ Grille de 4 restaurants avec images, noms et descriptions
- ✅ Footer avec informations de contact et liens
- ✅ Animations d'apparition au chargement

### 🍽️ Pages Restaurants (4 pages)

Chaque restaurant dispose d'une **page dédiée complète** :

#### Architecture de chaque page restaurant

- **Bannière** : Image d'en-tête du restaurant
- **En-tête** : Nom du restaurant + bouton favoris animé (❤️)
- **Menu** : Organisé par catégories (Entrées, Plats, Desserts)
- **Plats** : Affichage avec description et prix
- **Bouton de commande** : CTA principal pour la réservation
- **Footer** : Identique à la page d'accueil

#### Restaurants Partenaires

1. **À la française** - `a_la_francaise.html`
2. **La note enchantée** - `la_note_enchantee.html`
3. **La palette du goût** - `la_palette_du_gout.html`
4. **Le délice des sens** - `le_delice_des_sens.html`

### 🎨 Éléments Interactifs

- **Boutons CTA** : Survol avec changement de couleur et ombre
- **Cœur favoris** : Animation de remplissage au clic
- **Cartes restaurants** : Effet de survol avec ombre
- **Loader** : Animation à l'entrée du site (2-3 secondes)

---

## 🛠️ Stack Technologique

| Technologie | Version | Usage |
|-------------|---------|-------|
| **HTML5** | Standard | Structure sémantique et accessible |
| **CSS3** | Standard | Styles, animations et transitions |
| **SASS/SCSS** | Compilé | Préprocesseur CSS modulaire |
| **Git** | VCS | Gestion de version et commits |
| **GitHub** | Platform | Hébergement du repository |
| **GitHub Pages** | Hosting | Déploiement et mise en ligne |

---

## ✅ Validation & Qualité

Le projet respecte les **standards web professionnels** :

| Aspect | Statut | Détails |
|--------|--------|---------|
| **HTML W3C** | ✅ | Sémantique correcte, structure valide |
| **CSS W3C** | ✅ | Pas d'erreurs, warnings minimales |
| **Accessibilité** | ✅ | Contraste, alt text, ARIA labels |
| **Performance** | ✅ | CSS minifié, images optimisées, 60fps |
| **Cross-browser** | ✅ | Chrome, Firefox, Safari, Edge |
| **Responsive** | ✅ | Tests physiques et émulateurs |

---

## 🚀 Déploiement et Accès

Le site est **déployé en production** sur GitHub Pages et accessible en ligne :

### 🌐 Liens d'Accès

- **🔗 Site en ligne** : [https://weavyx.github.io/Ohmyfood/](https://weavyx.github.io/Ohmyfood/)
- **💻 Repository GitHub** : [https://github.com/Weavyx/Ohmyfood](https://github.com/Weavyx/Ohmyfood)

### 📥 Installation Locale

```bash
# 1. Cloner le repository
git clone https://github.com/Weavyx/Ohmyfood.git

# 2. Accéder au dossier
cd Ohmyfood

# 3. Ouvrir index.html dans le navigateur
# Option A: Double-clic sur index.html
# Option B: Utiliser un serveur local (Live Server extension VS Code)
```

### 🔄 Workflow de Développement

```bash
# Compiler SASS en CSS
sass assets/SASS/main.scss assets/CSS/main.css

# Minifier le CSS (si utilisation de CLI)
sass assets/SASS/main.scss assets/CSS/main.min.css --style=compressed
```

---

## 📚 Points Clés du Développement

### 🎯 Approche Mobile-First

- ✅ CSS de base optimisé pour petits écrans (< 768px)
- ✅ Media queries progressives pour tablettes et desktops
- ✅ Meilleure performance et chargement sur mobile
- ✅ Images et ressources optimisées pour bande passante faible

### 🎨 Animations CSS Pure (Pas de JavaScript)

- ✅ `@keyframes` pour animations complexes
- ✅ `transition` pour effets de survol fluides
- ✅ `transform` pour GPU-accélération (60fps)
- ✅ `animation-delay` pour stagger effects
- ✅ Respect de `prefers-reduced-motion` (accessibilité)

### 🏗️ Architecture SASS Modulaire

- ✅ Pattern 7-in-1 : abstracts, base, components, layouts, pages
- ✅ Variables centralisées et mixins réutilisables
- ✅ Séparation des concerns = maintenabilité
- ✅ Code DRY et scalable

### 🔧 Gestion Professionnelle

- ✅ **Git** : Commits descriptifs et historique clair
- ✅ **GitHub** : Repository public + traçabilité
- ✅ **GitHub Pages** : Déploiement automatique
- ✅ **Validation W3C** : HTML et CSS conformes

---

## 💡 Points Techniques Avancés

### 🎬 Animations Sophistiquées

```scss
// Exemple: Animation de cœur avec delay
@keyframes fillHeart {
  0% { transform: scale(1); }
  50% { transform: scale(1.2); }
  100% { transform: scale(1); }
}

.heart:active {
  animation: fillHeart 0.6s ease-in-out;
}
```

### 📐 Media Queries Réutilisables

```scss
// Mixin pour media queries fluides
@mixin tablet {
  @media (min-width: $breakpoint-tablet) {
    @content;
  }
}

// Utilisation
.container {
  width: 100%;

  @include tablet {
    width: 80%;
  }
}
```

### ⚡ Performance CSS

- **Minification** : CSS compressé pour production (gains de ~70%)
- **Compilation** : SASS compilé en CSS optimisé
- **Spécificité** : Éviter les `!important`, cascade utilisée correctement
- **GPU Acceleration** : Utilisation de `transform` et `opacity` (performant)

---

## 🎓 Ce Que j'ai Appris

### Compétences Techniques

- 🔹 **CSS avancé** : Animations, transitions, GPU-acceleration
- 🔹 **Architecture CSS** : Pattern SASS 7-in-1 modulaire
- 🔹 **Design Responsive** : Mobile-first, media queries intelligentes
- 🔹 **Performance Web** : Minification, optimisation assets
- 🔹 **Outils professionnels** : Git, GitHub, SASS compilation

### Compétences Soft

- 🔹 **Attention aux détails** : Pixel-perfect, animations fluides
- 🔹 **Pensée UX** : Feedback visuels, cohérence design
- 🔹 **Rigueur** : Tests multiples, validation standards
- 🔹 **Documentation** : Code structuré et README complet

---

## 🔮 Évolutions Possibles (Futures)

Pour des versions évoluées du projet :

### Court Terme (v2.0)

- [ ] Optimisation images WebP et lazy loading
- [ ] Menu déroulant animé sur mobile
- [ ] Notification toast pour favoris
- [ ] Mode sombre avec CSS variables

### Moyen Terme (v3.0)

- [ ] Panier de commande avec localStorage
- [ ] Formulaire de réservation validé
- [ ] Intégration API restaurants
- [ ] Système de notation/avis

### Long Terme (v4.0)

- [ ] Backend Node.js/Express
- [ ] Base de données (MongoDB)
- [ ] Authentification utilisateur
- [ ] Système de paiement intégré
- [ ] PWA (Progressive Web App)

---

## 🎯 Conclusion

**OhMyFood** est une **démonstration complète** des compétences front-end modernes :

- ✅ Design professionnel et cohérent
- ✅ Animations CSS sophistiquées (sans JavaScript)
- ✅ Code de qualité avec architecture modulaire
- ✅ Responsive parfait sur tous les appareils
- ✅ Standards web respectés (W3C validé)
- ✅ Site déployé en production (GitHub Pages)

**Valeur portfolio** : Démontre la capacité à créer des **interfaces web professionnelles**, respecter les **bonnes pratiques** et **déployer en production**.

---

## 👤 À Propos

**Développeur** : Maxime Nardelli (@Weavyx)
**Projet** : OhMyFood - Plateforme de Restauration
**Type** : Challenge de Formation
**Durée** : ~70 heures
**Statut** : ✅ Complété et Déployé
**Date de Création** : 2025

### 📞 Contact & Liens

- 🐙 **GitHub** : [@Weavyx](https://github.com/Weavyx)
- 🌐 **Portfolio** : [maximenardelli.fr](https://maximenardelli.fr)

---

## 📄 Licence

Ce projet fait partie d'un parcours de formation. Il représente un travail personnel créatif et reste propriété intellectuelle du développeur.

**Libre d'utilisation à titre d'exemple ou inspirationnel.**

---

**Merci d'avoir consulté ce README ! N'hésitez pas à explorer le code et le site en ligne.** 🍽️✨
