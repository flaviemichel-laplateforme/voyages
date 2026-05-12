# 🌍 Super Voyage - Site de Découverte des Destinations

Un projet collaboratif présentant des destinations de voyage fascinantes à travers le monde.

## 📝 Description

**Super Voyage** est un site web interactif conçu pour explorer et découvrir différentes destinations touristiques. Chaque destination est présentée avec des informations détaillées, des attractions, des conseils de voyage et des expériences culturelles uniques.

### Destinations disponibles

- 🍁 **Canada** - Paysages naturels et villes cosmopolites
- 🇩🇿 **Algérie** - Histoire, Sahara et culture méditerranéenne
- 🇳🇿 **Nouvelle-Zélande** - Fjords, culture maorie et aventures
- 🇦🇹 **Autriche** - Montagnes alpines et patrimoine musical
- 🇭🇰 **Hong-Kong** - Métropole dynamique et culture asiatique

## 👥 Équipe de développement

| Membres | GitHub                                                                     |
| ------- | -------------------------------------------------------------------------- |
| Dgino   | [@dgino-quatresous](https://github.com/dgino-quatresous)                   |
| Sofiane | [@Sofiane224434](https://github.com/Sofiane224434)                         |
| Malo    | [@malo-martiniani](https://github.com/malo-martiniani)                     |
| Flavie  | [@flaviemichel-laplateforme](https://github.com/flaviemichel-laplateforme) |
| Remy    | [@remy-dant](https://github.com/remy-dant)                                 |

## 📋 Répartition des tâches

- **Nouvelle-Zélande** - Développement et contenu

## 🛠️ Technologies utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Styling personnalisé
- **Tailwind CSS** - Framework utilitaire
- **JavaScript** - Interactivité

## 📂 Structure du projet

```
voyages/
├── index.html                          # Page d'accueil
├── assets/
│   ├── css/
│   │   ├── voyages.css                # Styles généraux
│   │   ├── canada.css
│   │   ├── algerie.css
│   │   ├── autriche.css
│   │   ├── hong-kong.css
│   │   └── nouvelle-zelande.css       # Styles Nouvelle-Zélande
│   ├── icons/                         # Icônes
│   └── images/                        # Images du site
├── pages/
│   ├── canada.html
│   ├── algerie.html
│   ├── autriche.html
│   ├── hong-kong.html
│   └── nouvelle-zelande.html          # Page Nouvelle-Zélande
└── README.md                          # Ce fichier
```

## 🎯 Fonctionnalités principales

✅ Navigation par menu déroulant vers toutes les destinations  
✅ Pages détaillées pour chaque pays avec des sections spécialisées  
✅ Design responsif adapté à tous les appareils  
✅ Contenu riche (descriptions, images, conseils de voyage)  
✅ Liens rapides vers les profils GitHub de l'équipe

## 🚀 Démarrage

1. Clonez ou téléchargez le projet
2. Ouvrez `index.html` dans votre navigateur web
3. Explorez les différentes destinations via le menu "Pays"

## 📱 Sections de chaque destination

Chaque page de destination inclut généralement :

- **Présentation générale** - Introduction au pays
- **Découverte de la nature** - Attractions naturelles
- **Culture locale** - Traditions et patrimoine
- **Aventures et activités** - Expériences palpitantes
- **Gastronomie** - Cuisine locale
- **Informations pratiques** - Conseils de voyage
- **Conclusion** - Appel à l'aventure

## 🎨 Personnalisation

Chaque destination possède son propre fichier CSS pour un style unique :

- `nouvelle-zelande.css` - Thème personnalisé pour la Nouvelle-Zélande

## 🎓 Page Nouvelle-Zélande - Compétences DWWM

### Développement d'une page statique

La page Nouvelle-Zélande (`pages/nouvelle-zelande.html`) démontre les compétences essentielles en développement web :

#### 📌 Compétences HTML5

- ✅ Structure sémantique complète (header, main, section, article)
- ✅ Intégration de métadonnées (charset UTF-8, viewport responsif)
- ✅ Liens de navigation internes et externes
- ✅ Utilisation de listes et conteneurs structurés
- ✅ Intégration d'images avec attributs alt descriptifs
- ✅ Utilisation d'ID et attributs pour l'accessibilité

#### 🎨 Compétences CSS3

- ✅ Feuille de style externe personnalisée (`nouvelle-zelande.css`)
- ✅ Classes et conteneurs stylisés `.container1` à `.container7`
- ✅ Mise en forme du contenu texte et des sections
- ✅ Design adapté à la thématique du pays
- ✅ Intégration avec Tailwind CSS pour la responsivité

#### 🔗 Architecture et navigation

- ✅ Système de navigation hiérarchisé (menu déroulant)
- ✅ Liens de navigation relative vers les autres pages
- ✅ Logo et header cohérent sur toutes les pages
- ✅ Menu membres avec liens externes GitHub

#### 📝 Contenu structuré

- ✅ Titres hiérarchisés (h1, h2)
- ✅ Sections thématiques organisées :
  - Découverte de la nature (Milford Sound, parcs nationaux)
  - Culture maorie
  - Aventures en plein air
  - Gastronomie locale
  - Informations pratiques
- ✅ Paragraphes descriptifs et informatifs
- ✅ Liens internes d'ancrage (#milford-sound, #culture-maorie, etc.)

#### 💻 Fichiers associés

- `pages/nouvelle-zelande.html` - Page statique HTML
- `assets/css/nouvelle-zelande.css` - Styles personnalisés
- `assets/css/voyages.css` - Styles communs
- `assets/images/nouvelle-zelande.jpg` - Image illustrative

### Compétences validées

- ✨ Développement de page HTML statique
- ✨ Stylisation CSS personnalisée
- ✨ Intégration de contenu multimédia
- ✨ Respect des standards web et accessibilité
- ✨ Collaboration au sein d'un projet collectif

## � Déploiement sur Plesk avec GitHub

### Architecture de déploiement

Le projet utilise une intégration **GitHub → Plesk** pour un déploiement automatisé et à jour en permanence.

### Prérequis

- ✅ Un compte Plesk actif
- ✅ Un repository GitHub avec le code du projet
- ✅ Accès administrateur au panneau Plesk

### Étapes de déploiement initial

#### 1. Accéder au panneau Plesk

- Connectez-vous à votre compte Plesk
- Naviguez vers le domaine cible dans **Domaines**

#### 2. Accéder à Git

- Sélectionnez votre domaine
- Allez dans **Repository Git** (ou **Git**)
- Sélectionnez **HTTPS** ou **SSH** selon votre configuration

#### 3. Cloner le repository GitHub

- Entrez l'URL du repository GitHub
- Exemple : `https://github.com/username/voyages.git`
- Cliquez sur **Cloner le repository**

#### 4. Configurer le répertoire de déploiement

- Définissez le chemin de déploiement : `httpdocs` (par défaut)
- Nommez votre application : `reservationdesalles`
- Sélectionnez la branche : **main**

#### 5. Valider la configuration

- Cliquez sur **OK** pour créer la connexion GitHub
- Plesk crée automatiquement le lien et clone le repository

### Workflow de déploiement continu

Après la configuration initiale, utilisez ce workflow pour maintenir votre site à jour :

#### ✅ Avant de déployer

1. **Assurez-vous que vos changements sont sur GitHub**
   - Faites un `git push` depuis votre environnement local
   - Assurez-vous que tout est commité sur la branche `main`

2. **Vérifier l'état du repository dans Plesk**
   - Allez dans **Domaines** → votre domaine → **Repository Git**
   - Visualisez le statut de la dernière synchronisation

#### 🔄 Mettre à jour le code (Pull Now)

1. Dans Plesk, allez dans **Repository Git**
2. Cliquez sur **Pull Now** (ou **Tirer les modifications**)
   - Cela récupère les derniers changements de GitHub
   - Vérifiez que tous les fichiers sont à jour
   - Utile avant de déployer si d'autres membres de l'équipe ont modifié le code

#### 🚀 Déployer les changements (Deploy Now)

1. Après un **Pull Now**, cliquez sur **Deploy Now** (ou **Déployer**)
   - Cela applique les changements sur le serveur web
   - Le site devient accessible à jour immédiatement
   - Les fichiers sont synchronisés dans `httpdocs`

### Workflow complet type

```
1. Développement local
   ↓
2. git push vers GitHub (branche main)
   ↓
3. Accès Plesk → Repository Git
   ↓
4. Cliquer Pull Now (optionnel mais recommandé)
   ↓
5. Cliquer Deploy Now
   ↓
6. ✅ Site en production mis à jour
```

### Bonnes pratiques

🔹 **Testez toujours localement** avant de pusher vers GitHub  
🔹 **Utilisez Pull Now** pour vérifier les changements avant de déployer  
🔹 **Commitez régulièrement** avec des messages clairs  
🔹 **Gardez une branche main stable** pour la production  
🔹 **Communiquez avec l'équipe** avant un déploiement

### Vérification après déploiement

Après chaque déploiement, vérifiez :

- ✅ Accès au domaine (`https://votredomaine.com`)
- ✅ Chargement des pages HTML
- ✅ Affichage des images dans `assets/images/`
- ✅ Application des styles CSS
- ✅ Navigation entre pages fonctionnelle
- ✅ Menu déroulant des pays actif
- ✅ Liens GitHub dans la section Membres

### Troubleshooting

**❌ Deploy Now n'apparaît pas :**

- Effectuez d'abord un "Pull Now"
- Vérifiez les permissions du repository

**❌ Les fichiers n'ont pas été mis à jour :**

- Vérifiez que vos commits sont sur GitHub branche `main`
- Cliquez à nouveau sur "Pull Now" puis "Deploy Now"

**❌ Les images ou CSS ne s'affichent pas :**

- Vérifiez les chemins dans les fichiers HTML
- Assurez-vous que le dossier `assets/` a les bonnes permissions

### Avantages du déploiement GitHub → Plesk

✨ Déploiement centralisé depuis GitHub  
✨ Versionning du code préservé  
✨ Mise à jour rapide en un clic  
✨ Historique complet des déploiements  
✨ Synchronisation facile en équipe

## �📞 Support et contribution

Pour contribuer ou suggérer des améliorations, veuillez contacter les membres de l'équipe.

---
