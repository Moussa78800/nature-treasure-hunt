# 🌿 La Chasse aux Trésors de la Nature

Un jeu d'exploration et de collecte en 3D dans un village de campagne paisible, développé en HTML/JavaScript pur avec Three.js.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Three.js](https://img.shields.io/badge/Three.js-r160-green)
![License](https://img.shields.io/badge/license-MIT-yellow)

## 🎮 Description

Explorez un village campagnard baigné de lumière dorée et collectez un maximum de trésors en 5 minutes ! Ce jeu combine exploration libre, collecte d'objets et ambiance sonore immersive, le tout généré procéduralement sans aucun asset externe.

## ✨ Fonctionnalités

### Monde immersif
- **Terrain procédural** : collines vallonnées générées par bruit de Perlin
- **Ciel dynamique** : dôme avec dégradé golden hour, soleil lumineux et nuages dérivants
- **Village vivant** : 6 maisons avec fenêtres illuminées et fumée de cheminée
- **Végétation** : 55+ arbres avec balancement au vent, fleurs, rochers, herbe
- **Créatures** : oiseaux en vol circulaire, papillons, pollen flottant

### Système de jeu
- **5 types de collectibles** avec valeurs croissantes :
  - 🌸 Fleurs (10 pts) - 50 exemplaires
  - 🦋 Papillons (25 pts) - 15 exemplaires, fuient le joueur
  - 🍄 Champignons (50 pts) - 8 exemplaires, cachés près des arbres
  - 💎 Cristaux (100 pts) - 5 exemplaires, sur les hauteurs
  - ⭐ Étoiles magiques (250 pts) - 3 exemplaires, très rares
- **Power-ups** : Aimant (attire les objets) ou Points x2
- **Système de combo** : multiplicateur jusqu'à x8 pour collectes rapides
- **Timer de 5 minutes** avec écran de fin et classement

### Train réaliste
- Passage toutes les 55 secondes
- Locomotive + 5 wagons colorés avec roues animées
- Cornes de brume réalistes (stéréo)
- Passage à niveau avec barrière et feux clignotants
- Son de roulement panoramique suivant la position du train

### Audio procédural
- **Ambiance** : vent filtré, chants d'oiseaux aléatoires, grillons
- **Pas du joueur** : synchronisés avec le head-bob
- **Collectes** : sons mélodiques différents par type d'objet
- **Train** : klaxon deux tons, grondement rythmé, cloche du passage à niveau

### Contrôles
- **WASD** : déplacement
- **Souris** : regard (pointer lock)
- **Shift** : sprint
- **Espace** : saut
- **F** : afficher/masquer le compteur FPS

## 🚀 Installation et lancement

### Méthode simple (recommandée)
1. Téléchargez le fichier `index.html`
2. Ouvrez-le directement dans Chrome, Firefox ou Edge
3. Cliquez pour commencer à jouer

### Avec serveur local (optionnel)