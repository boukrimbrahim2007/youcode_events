# 🎉 YouCode Events

**YouCode Events** est un site web statique réalisé en HTML5 et CSS3 dans le cadre d’un projet collectif de formation à YouCode. Il présente les ateliers, conférences, hackathons et rencontres avec des professionnels dans une interface adaptée aux ordinateurs, tablettes et mobiles.

[Voir le site en ligne](https://boukrimbrahim2007.github.io/youcode_events/)

## 📌 Contexte et objectif

Les événements de YouCode sont annoncés sur plusieurs canaux, sans point d’entrée unique. Ce projet vise à centraliser leur présentation et à préparer un parcours de consultation et d’inscription.

Le travail porte sur le maquettage, l’intégration HTML et CSS, les media queries et la collaboration sur un dépôt GitHub commun. Il s’agit d’un site fictif à vocation pédagogique.

## 👥 Équipe, rôles et répartition du travail

| Membre | Rôles | Contributions |
| --- | --- | --- |
| **ET-TAYA Younes** | Développement front-end, maquettage | Réalisation des pages `index.html` et `Intervenants.html`, navbar ordinateur et tablette, préparation des images dans `assets/`, travail sur Figma et rédaction du `README.md`. |
| **BOUKRIM Brahim** | Développement front-end, responsive et présentation | Réalisation de la page `events.html`, navbar mobile, footer pour toutes les versions, travail sur `responsive.css` et préparation de la présentation du projet. |


| Page | Contenu et état |
| --- | --- |
| `index.html` | Page d’accueil réalisée par Younes |
| `Intervenants.html` | Page des intervenants réalisée par Younes |
| `events.html` | Page des événements réalisée par Brahim |
| `details.html` | Navbar et footer intégrés, contenu principal à compléter |
| `inscrire.html` | Navbar et footer intégrés, contenu principal à compléter |


## 🛠️ Technologies utilisées

| Technologie | Utilisation |
| --- | --- |
| **HTML5** | Structure et contenu des pages |
| **CSS3** | Mise en forme du site |
| **Flexbox** | Alignement et disposition des éléments |
| **CSS Grid** | Organisation des contenus en grilles |
| **Media queries** | Adaptation aux différentes tailles d’écran |

### Outils

- **Figma** pour le travail sur la maquette.
- **Git et GitHub** pour la gestion des versions et la collaboration.
- **Jira** pour le tableau de suivi du projet.
- **Visual Studio Code** pour l’édition du code.

## 📂 Structure du projet

```text
youcode_events/
├── assets/                 # Images et ressources visuelles
│   └── screenshots/        # Captures utilisées dans ce README
│       ├── details-Atelier.jpg
│       ├── footer-mobile.jpg
│       ├── footer-laptop.png
│       ├── navbar-laptop.png
│       └── navbar-mobile.png
├── css/
│   ├── responsive.css      # Media queries et styles responsive
│   └── style.css           # Styles principaux
├── details.html            # Contenu principal à compléter
├── events.html             # Liste des événements
├── index.html              # Page d’accueil
├── inscrire.html           # Contenu principal à compléter
├── Intervenants.html       # Présentation des intervenants
└── README.md               # Documentation du projet
```

Le dossier `assets/screenshots/` doit contenir cinq  images indiquées pour afficher les aperçus en fin de document. Les noms et extensions doivent être respectés exactement.

## 🚀 Installation et lancement

### Cloner le dépôt

```bash
git clone https://github.com/boukrimbrahim2007/youcode_events.git
cd youcode_events
```

### Lancer avec Live Server

1. Ouvrir le dossier racine du projet dans Visual Studio Code.
2. Installer l’extension **Live Server**, si nécessaire.
3. Faire un clic droit sur `index.html`.
4. Sélectionner **Open with Live Server**.
## ovrire le projet 
Ouvrir ensuite (https://boukrimbrahim2007.github.io/youcode_events/)

Aucune installation de dépendances applicatives n’est nécessaire. Une connexion Internet est utile pour charger les ressources externes référencées par les pages, notamment les polices et icônes.

## 🔀 Workflow Git de l’équipe

Chaque membre travaille dans ses branches. Les modifications sont regroupées dans la branche commune **`developement`**.

### Branches utilisées

| Membre ou usage | Branches |
| --- | --- |
| **ET-TAYA Younes** | `feateure/readme`, `feateure/intervenants`, `page/index`, `feature/index` |
| **BOUKRIM Brahim** | `revert-5-evenement`, `fix/polishing_page1and2` |
| **Intégration commune** | `developement` |


### Étapes et règles de Pull Request

1. Réaliser les modifications dans une branche de travail.
2. Enregistrer les modifications avec un commit.
3. Envoyer les commits sur GitHub avec `git push`.
4. Ouvrir une **Pull Request** vers `developement`.
5. Demander au coéquipier de relire les modifications.
6. Apporter les corrections nécessaires après la relecture.
7. Fusionner la Pull Request après l’approbation du coéquipier.

La relecture croisée permet à chaque membre de vérifier et de comprendre les modifications de l’autre avant leur intégration.

### Format des messages de commit

Pendant le projet, l’équipe a utilisé des messages descriptifs au **format libre**, en français par **ET-TAYA Younes** ou en anglais **BOUKRIM Brahim**.

Exemples communiqués par les membres :

| Membre | Exemples |
| --- | --- |
| **Younes** | `j’ai terminé la page intervenants` |
| **Brahim** | `finished page evenement`, `a small fix in nav`, `a new html file` |

Le brief demande la convention `type: description`. Elle n’a pas été appliquée systématiquement aux messages ci-dessus et constitue un point d’amélioration pour les prochains commits.

## 📱 Responsive et points de rupture

Les règles d’adaptation sont regroupées dans `css/responsive.css`. Les principaux points de rupture utilisés sont **768 px** et **1024 px**.

| Point de rupture | Adaptation | Justification |
| --- | --- | --- |
| **768 px** | Bascule entre navigation mobile et navigation pour écran plus large, réorganisation des contenus | Sur un écran étroit, le menu hamburger réduit l’encombrement et les contenus empilés restent lisibles. Un écran plus large permet d’afficher les liens et davantage de contenus côte à côte. |
| **1024 px** | Adaptation des grilles entre les largeurs intermédiaires et les grands écrans | Deux colonnes permettent de conserver des cartes suffisamment larges sur tablette, tandis que les grands écrans permettent d’afficher trois colonnes pour les grilles concernées. |

Flexbox facilite l’alignement des éléments, tandis que CSS Grid permet de faire évoluer le nombre de colonnes selon la largeur disponible.

Le menu mobile utilise les éléments HTML natifs `<details>` et `<summary>` pour afficher et masquer les liens sans JavaScript.

## 🎨 Liens du projet

- [Site en ligne](https://boukrimbrahim2007.github.io/youcode_events/)
- [Dépôt GitHub](https://github.com/boukrimbrahim2007/youcode_events)
- [Maquette Figma](https://www.figma.com/design/UId1ZzEzO3soOAhjV1bW37/Voir-Details?node-id=0-1)
- [Tableau Jira](https://boukrimbrahim2007.atlassian.net/jira/software/projects/SCRUM/boards/1)

L’accès à Figma et à Jira dépend des autorisations de partage configurées sur ces outils.

## 📸 Aperçus du projet

### Visuel de détail de l’atelier

Le visuel ci-dessous présente le détail de l’atelier. Il ne constitue pas une confirmation que le contenu de `details.html` est entièrement intégré.

![Visuel de détail de l’atelier](assets/screenshots/details-Atelier.jpg)

### Navbar — Ordinateur

![Barre de navigation sur ordinateur](assets/screenshots/navbar-laptop.png)

### Navbar — Mobile

![Barre de navigation sur mobile](assets/screenshots/navbar-mobile.png)

### Footer — Ordinateur

![Pied de page sur ordinateur](assets/screenshots/footer-laptop.png)

### Footer — Mobile

![Pied de page sur mobile](assets/screenshots/footer-mobile.jpg)

---

Projet de formation réalisé par **ET-TAYA Younes** et **BOUKRIM Brahim** à YouCode.
