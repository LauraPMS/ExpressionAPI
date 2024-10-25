# 📘 Expression API

**Description rapide** : Ce projet est une initiation a l'analyse de données d'images. L'analyse permet de reconnaitre les expressions facial en direct webcam ou d'apres une vidéo et envoie un fichier excel avec le pourcentges des expressions reconnu.

![Project Badge](https://img.shields.io/badge/version-1.0-blue.svg) ![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)

---

## 🌟 Sommaire

- [Présentation](#présentation)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Exemples](#exemples)
- [Contributions](#contributions)
- [Contact](#contact)

---

## 🎯 Présentation 

Ce projet a été réalisé en stage de première année de BTS SIO. 
Nous avions pour but d'analyser les mouvements et les gestes clé lors d'un tournoi de tennis (opendu17.fr) qui permettrai de prédire si un joueur va marquer.
Cette première version est une initiation a l'analyse de data. Vous trouverez ici seulement le contenue de la reconnaissance d'expression faciale.
Nous avons utilisé FaceAPI.js qui est une api capable de reconnaitre le squelette d'un corps et de mapper le visges a l'aide de différents points. Cela nous renvoie des données dans un fichier excel frame par frame. 
La version final avec les statistiques n'est pas disponible sur ce repo car elle appartient a l'entreprise.
---


## 🔧 Prérequis

Pour exécuter ce projet, vous aurez besoin de :

- **Langages et technologies** : JavaScript, API.
- **Environnement** : créer un serveur python suffit largement.
- **Analyse de Data**
- **Comment fonctionne l'API** : [Cliquer ici](https://justadudewhohacks.github.io/face-api.js/docs/index.html)

---

## 🚀 Installation

Pour installer et configurer le projet, suivez ces étapes :

1. Clonez le dépôt :
    ```bash
    git clone https://github.com/LauraPMS/ExpressionAPI.git
    cd ExpressionAPI.git
    ```
2. Lancer un serveur python :
    ```bash
    python -m http.server 8000
    ```


---

## 💻 Utilisation

Pour lancer le projet, exécutez la commande suivante :

1. Rendez vous sur :
    ```bash
    http://localhost:8000
    ```
2. Une fois sur l'application vous aurez 2 choix :
   - Upload Video :
     Fournissez une vidéo avec des corps ou visage bien visible.
   - Webcam :
     Accepter l'accès de votre webcam a votre navigateur.*
   Une fois fini, vous n'avez plus cas télécharger en appuyant sur ... **Telecharger**!

3. Cette dernière action vous téléchargera un fichier excel avec les données des different points du squellette

--- 
#### Pour toute demande je reste joignable par mail : laurapms.codex@gmail.com
