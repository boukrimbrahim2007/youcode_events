# 🎉 YouCode Events

**YouCode Events** est un site web réalisé avec **HTML5 et CSS3** dans le cadre d’un projet de formation. Il présente les ateliers, conférences, hackathons et rencontres de YouCode dans une interface adaptée aux ordinateurs et aux mobiles.

## 📌 Présentation du projet

Le site comprend une page d’accueil, une liste des événements, une page de détails, une présentation des intervenants et une page d’inscription. Il s’agit d’un projet front-end pédagogique, avec des contenus de démonstration.

## 💻 Version ordinateur portable

### Barre de navigation — Navbar

La barre de navigation affiche le logo **YouCode Events** à gauche et les liens principaux à droite :

- **Accueil** — Accès à la page d’accueil, avec un indicateur de page active.
- **Événements** — Consultation des événements.
- **Intervenants** — Présentation des intervenants et partenaires.
- **S’inscrire** — Bouton d’accès à la page d’inscription.

![Barre de navigation sur ordinateur](assets/screenshots/navbar-laptop.png)

### Pied de page — Footer

Le pied de page utilise un fond sombre et regroupe trois espaces :

- **YouCode Events** — Une courte présentation du site.
- **Navigation** — Les liens vers les principales pages.
- **Contact** — Une adresse de démonstration et les villes Youssoufia, Safi et Nador.

Une mention précise que le site est fictif et réalisé dans le cadre d’une formation.

![Pied de page sur ordinateur](assets/screenshots/footer-laptop.png)

## 📱 Version mobile

### Barre de navigation — Navbar

Sur mobile, le logo reste à gauche et une icône de menu hamburger apparaît à droite. Les éléments HTML natifs `<details>` et `<summary>` permettent d’afficher les liens de navigation sans JavaScript.

![Barre de navigation sur mobile](assets/screenshots/navbar-mobile.png)

Les media queries CSS adaptent la navigation et la disposition des contenus aux différentes tailles d’écran, avec des règles autour de **768 px** et **1024 px**.

## 🛠️ Technologies utilisées

| Technologie | Utilisation |
| --- | --- |
| HTML5 | Structure des pages et menu mobile natif |
| CSS3 | Mise en forme, Flexbox, Grid et adaptation aux écrans |
| Font Awesome | Icônes de l’interface |
| Google Fonts | Polices de caractères |
| Git et GitHub | Gestion des versions et collaboration |

## 📂 Architecture du projet

Arborescence du projet telle qu’elle apparaît dans l’explorateur de fichiers :

```text
youcode_events/
├── assets/
│   ├── accessibiliter.png
│   ├── ajonda.png
│   ├── atelier.png
│   ├── bnadm.bleu.png
│   ├── bnadm.png
│   ├── bnadm.red.png
│   ├── branche.png
│   ├── laptop.png
│   └── transforme.png
├── css/
│   ├── responsive.css
│   └── style.css
├── html/
│   ├── details.html
│   ├── events.html
│   ├── index.html
│   ├── inscrire.html
│   └── Intervenants.html
├── README.md
└── test.html
```

| Fichier ou dossier | Rôle |
| --- | --- |
| `assets/` | Images et ressources visuelles |
| `css/responsive.css` | Adaptation des mises en page aux tailles d’écran |
| `css/style.css` | Styles principaux du site |
| `html/details.html` | Détails d’un événement |
| `html/events.html` | Liste des événements |
| `html/index.html` | Page d’accueil |
| `html/inscrire.html` | Page d’inscription |
| `html/Intervenants.html` | Présentation des intervenants |
| `README.md` | Documentation du projet |
| `test.html` | Page de test |

**Captures du README :** pour afficher les trois aperçus ci-dessus, ajouter le dossier `assets/screenshots/` fourni avec ce README. Ce dossier de documentation vient en complément de l’arborescence présentée et contient `navbar-laptop.png`, `footer-laptop.png` et `navbar-mobile.png`.

## 🚀 Lancer le projet

### 1. Cloner le dépôt

```bash
git clone https://github.com/boukrimbrahim2007/youcode_events.git
cd youcode_events
```

### 2. Démarrer un serveur local

Ouvrir le dossier racine du projet dans **Visual Studio Code**, puis lancer `html/index.html` avec l’extension **Live Server**.

Il est également possible d’utiliser Python depuis la racine du projet :

```bash
python -m http.server 8000
```

Accéder ensuite à [http://localhost:8000/html/index.html](http://localhost:8000/html/index.html).

Le serveur doit être lancé depuis la racine du dépôt, car les pages utilisent des chemins comme `/css/style.css` et `/assets/ajonda.png`. Une connexion Internet est nécessaire pour charger les polices et les icônes externes.

## 🎯 Objectifs pédagogiques

- Construire un site de plusieurs pages avec HTML et CSS.
- Réaliser une barre de navigation pour ordinateur et mobile.
- Structurer les mises en page avec Flexbox et CSS Grid.
- Utiliser les media queries pour adapter l’affichage.
- Organiser les fichiers et suivre les modifications avec Git et GitHub.

## 🔗 Dépôt GitHub

[boukrimbrahim2007 / youcode_events](https://github.com/boukrimbrahim2007/youcode_events)

---

Projet réalisé dans le cadre d’une formation au développement web à YouCode.
