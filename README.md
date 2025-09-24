# 🚀 Campagne Vienne l'insoumise (2026)

**Slogan :** Nous ferons mieux.

Ce dépôt contient le code source de la page d'accueil de la campagne municipale "Vienne l'insoumise" pour les élections de 2026 à Vienne (Isère). Le site est conçu pour être simple à maintenir, entièrement *responsive* (adapté aux mobiles) et déployé via GitHub Pages.

## 🛠️ Structure du Projet

| Fichier/Dossier | Rôle |
| :--- | :--- |
| `index.html` | La structure principale de la page (HTML sémantique). |
| `style.css` | La feuille de styles contenant l'identité visuelle complète. |
| **`images/`** | **IMPORTANT :** Dossier de destination pour toutes les photos (logo, bannière, actions). |
| `README.md` | Ce guide. |

## 🌐 Déploiement sur GitHub Pages

Suivez ces étapes simples pour rendre le site visible :

1.  **Créez le Dépôt :** Téléversez tous les fichiers (une fois que vous les aurez tous) dans un nouveau dépôt GitHub.
2.  **Activez Pages :**
    * Allez dans l'onglet **"Settings"** (Paramètres) de votre dépôt.
    * Dans le menu de gauche, sélectionnez **"Pages"**.
    * Sous **"Source"**, assurez-vous que la source est définie sur **"Deploy from a branch"**.
    * Sous **"Branch"** (Branche), sélectionnez **`main`** (ou `master` selon votre configuration) et choisissez le dossier **`/(root)`**.
    * Cliquez sur **"Save"** (Enregistrer).
3.  **Attendez :** GitHub prendra quelques minutes pour construire et publier le site. L'URL de votre site sera affichée dans cette même section "Pages".

## 🖼️ Guide d'Insertion des Images

Le code HTML et CSS est prêt pour vos visuels. Voici les noms et emplacements attendus :

| Fichier Image | Emplacement dans le site |
| :--- | :--- |
| `images/logo.png` | En-tête de la navigation (taille réduite). |
| `images/banniere.jpg` | Section Héros (grande image de fond). |
| `images/porte-a-porte.jpg` | Carte d'action n°1. |
| `images/inscriptions.jpg` | Carte d'action n°2. |
| `images/reunions.jpg` | Carte d'action n°3. |
| `images/equipe.jpg` | Section Contact / À propos (optionnel). |

Pour que le site fonctionne correctement, **assurez-vous que toutes vos images sont placées dans le dossier `images/`** que vous créerez.

---

Maintenant que vous avez les instructions, quel fichier souhaiteriez-vous que je vous donne ? Je suggère de passer au **`style.css`** pour que nous puissions immédiatement appliquer la charte graphique et les polices, ou alors le **`index.html`** pour la structure principale.
