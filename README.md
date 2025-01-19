# **GESTION ET SPECIFICITÉS DU PROJET**

## 🤝**NOMBRE DE COLLABORATEURS pour le projet collectif** :
     4

## ⌛️**TEMPS de conception et démonstration**: 
     2 semaines

## ❓**THEME de l'API CHOISI et OBJECTIFS:**

📌  **"HeroesHub"**, utilisation de l'API [SuperHero API](https://www.superheroapi.com/)
  
📌  **L'application a pour but de fournir une interface utilisateur permettant :**

           * De rechercher des super-héros à l'aide d'un nom.
           
           * D'obtenir des informations détaillées sur le super-héros sélectionné.
          
           * De gérer les erreurs liées à des recherches infructueuses ou à l'API.
           
           * Elle intègre aussi une fonctionnalité audio pour enrichir l'expérience utilisateur.
  

## 📋**ORGANISATION de TRAVAIL et OUTILS:**

### - 💻  Selon la répartition des tâches, en Mob/Split Programming

### - 🔧 Outils utilisés :
  
- **Notion** : ToDo/Task Timeline/Assets
    
- **Git et Git Hub**
    
- **VSCode**
    
- **FrameO** pour le croquis et **Figma** pour la maquette
    

<img width="1377" alt="HeroesHub-Menu" src="https://github.com/user-attachments/assets/c017a310-77a0-4a28-aa86-f267d622cd1a" />

<img width="1327" alt="HeroesHub-CharacterPage" src="https://github.com/user-attachments/assets/262d5612-3d19-4bf2-8814-bbac4932725a" />

## ✔️**MVP : FONCTIONNALITES et OBJECTIFS dans le CADRE du PROJET:**

### 🔎**ETAPES utilisateur:**
   

**1. Recherche dans le menu (heroApiMenu.js):**

          - L'utilisateur entre un nom de héros et lance une recherche.
          
          - Si le héros est trouvé, il est redirigé vers la page des détails du héros.
          
          - En cas d'erreur (entrée vide ou héros introuvable), des messages appropriés sont affichés.

**2. Affichage des détails (heroApi.js) :**

          - La page dédiée récupère le nom du héros dans l'URL.
          
          - Les données du héros sont récupérées depuis l'API et affichées dynamiquement.

    
### 📁 **FONCTIONNALITES des fichiers principaux:**


### 💾 **1.heroApiMenu.js**

✳️**Objectif principal** : Gérer la recherche de super-héros depuis une barre de recherche située dans un menu ou
          une partie spécifique de l'application.

✅ **Fonctionnalités principales** :
   
   📌**Validation de la recherche :**
   
            - Vérifie si un héros correspondant au nom entré existe dans l'API.
            
            - Si le héros est valide, l'utilisateur est redirigé vers une autre page (heroAPI.html) avec le nom du héros
                 passé en paramètre dans l'URL.
   
   📌**Gestion des événements utilisateur :**
   
            - Gère les clics sur un bouton de recherche.
            
            - Prend en charge l'appui sur la touche "Entrée" pour déclencher la recherche.
   
  📌**Gestion des erreurs :**
   
            - Affiche des messages d'erreur si l'entrée est vide ou si aucun héros correspondant n'est trouvé.

### 💾 **2.heroApi.js**
✳️**Objectif principal** : Gérer l'affichage détaillé d'un super-héros sur une page dédiée après la recherche.

✅**Fonctionnalités principales :**
   
   📌**Récupération des données :**
   
            - Envoie une requête à l'API pour rechercher un super-héros en fonction du nom passé dans l'URL.
            
            - Affiche les informations du héros si elles sont trouvées (nom, image, éditeur, statistiques, etc.).
   
   📌**Affichage dynamique :**
   
            - Met à jour les éléments HTML de la page avec les données du héros, y compris le nom, l'image, la biographie,
                 et les statistiques (intelligence, force, etc.).
   
   📌**Gestion des événements utilisateur :**
   
            - Gère les clics sur le bouton de recherche et l'appui sur "Entrée" dans le champ de saisie.
   
   📌**Gestion des erreurs :**
   
            - Fournit des messages pour des requêtes infructueuses ou des erreurs liées à l'API.


## ➕**VERSION 2: OBJECTIFS et FONCTIONNALITES pour une version 2 du projet (en cours de réalisation):**

   ✅ **Fonctionnalité audio intégrée :**

Les deux fichiers incluent aussi une configuration pour gérer un lecteur audio :

    📌Lecture et pause d'un fichier audio.
    
    📌Contrôle du volume et de la balance (panning).
    
    📌Gestion de l'état du lecteur (activé/désactivé). 
    
   🌀 **Amelioration CSS:**
   
     📌Rendre l'interface responsive.

    

    

    
