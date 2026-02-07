---
title: "Ordinateur low-tech"
meta_title: "Construire un Ordinateur Low-tech - Tutoriel Low-tech"
description: "Un modèle d'ordinateur basique mais répondant néanmoins à la plupart de nos besoins quotidiens. Le tout, pour un prix n'excédant pas 30 euros!"
date: 2024-01-20T00:00:00Z
image: "/images/tutorials/ordinateur-low-tech/main.jpg"
categories: ["Technologie", "Électronique"]
author: "Low-tech Lab"
tags: ["ordinateur", "raspberry-pi", "recyclage", "hors-ligne"]
draft: false

# Tutorial specific fields
difficulty: "Moyen"
duration: "1 jour"
cost: "30€"
license: "CC BY-SA"
---

Un modèle d'ordinateur basique mais répondant néanmoins à la plupart de nos besoins quotidiens. Le tout, pour un prix n'excédant pas 30 euros ! Ce tutoriel vous guide dans la création d'un ordinateur de bureau fonctionnel et abordable utilisant un Raspberry Pi et des composants récupérés pour les tâches bureautiques de base, la navigation web et l'utilisation multimédia simple.

## Matériel nécessaire

![Kit Raspberry Pi Zero W](/images/tutorials/ordinateur-low-tech/materiel-kit.jpg)

![Détails du Raspberry Pi Zero W](/images/tutorials/ordinateur-low-tech/materiel-details.png)

![Clavier, souris et écran](/images/tutorials/ordinateur-low-tech/materiel-peripheriques.jpg)

- Raspberry Pi Zero W ou Pi Zero 2 W
- Carte MicroSD 64GB
- Clavier USB ou sans fil (récupération)
- Souris USB ou sans fil (récupération)
- Écran avec connexion HDMI (récupération)
- Câble HDMI
- Adaptateur micro HDMI
- Adaptateur micro USB
- Source d'alimentation 5V
- Ordinateur avec connexion internet (pour la configuration initiale)

## Caractéristiques principales

- Alternative d'ordinateur de bureau à faible coût
- Accès à Wikipédia hors ligne grâce à Kiwix
- Supporte les applications bureautiques et la navigation internet
- Respectueux de l'environnement grâce au recyclage de composants

## Étape 1 - Préparer la carte SD : Installation de Raspberry Pi OS

![Raspberry Pi Imager](/images/tutorials/ordinateur-low-tech/etape1-rpi-imager.png)

Téléchargez le logiciel Raspberry Pi Imager sur votre ordinateur de configuration. Formatez votre carte microSD et écrivez le dernier Raspberry Pi OS dessus à l'aide de l'Imager. Une fois terminé, insérez la carte microSD dans votre Raspberry Pi.

![Configuration de l'Imager](/images/tutorials/ordinateur-low-tech/etape1-capture1.jpg)

![Sélection de l'OS](/images/tutorials/ordinateur-low-tech/etape1-capture2.jpg)

![Écriture sur la carte SD](/images/tutorials/ordinateur-low-tech/etape1-capture3.jpg)

## Étape 2 - Mise sous tension et configuration

![Alimentation du Raspberry Pi](/images/tutorials/ordinateur-low-tech/etape2-alimentation.jpg)

Connectez tous les périphériques (clavier, souris, écran) à votre Raspberry Pi **avant** de le mettre sous tension. Une fois alimenté, suivez l'assistant de configuration pour configurer :
- La connexion Wi-Fi
- Les préférences linguistiques
- Les paramètres régionaux
- Le compte utilisateur

**Note importante :** Si vous remarquez un éclair dans le coin supérieur droit de l'écran, cela signifie que votre Raspberry Pi n'est pas suffisamment alimenté. Il est recommandé d'utiliser une alimentation officielle.

## Étape 3 - Accès à Wikipédia hors ligne

![Kiwix](/images/tutorials/ordinateur-low-tech/etape3-kiwix.png)

![Logo Kiwix](/images/tutorials/ordinateur-low-tech/etape3-kiwix-logo.png)

L'une des fonctionnalités clés de cet ordinateur low-tech est la possibilité d'accéder à Wikipédia sans connexion internet en utilisant le logiciel Kiwix. Vous avez deux options d'implémentation :

## Étape 4 - Option 1 : Lecteur Kiwix

![Kiwix Reader](/images/tutorials/ordinateur-low-tech/etape4-kiwix-reader.jpg)

Téléchargez et installez l'application Kiwix Reader. Sélectionnez et téléchargez des fichiers de contenu ZIM spécifiques à la langue (ces fichiers contiennent des archives Wikipédia compressées). Installez-les localement sur votre Raspberry Pi pour un accès hors ligne.

**Avantages :**
- Simple à utiliser
- Accès direct sur l'ordinateur
- Consultation locale du contenu

## Étape 5 - Option 2 : Hotspot Kiwix

![Kiwix Hotspot - Installation](/images/tutorials/ordinateur-low-tech/etape5-hotspot1.jpg)

![Kiwix Hotspot - Configuration](/images/tutorials/ordinateur-low-tech/etape5-hotspot2.jpg)

![Kiwix Hotspot - Sélection du contenu](/images/tutorials/ordinateur-low-tech/etape5-hotspot3.jpg)

![Kiwix Hotspot - Téléchargement](/images/tutorials/ordinateur-low-tech/etape5-hotspot4.jpg)

![Kiwix Hotspot - Écriture](/images/tutorials/ordinateur-low-tech/etape5-hotspot5.jpg)

![Kiwix Hotspot - Terminé](/images/tutorials/ordinateur-low-tech/etape5-hotspot6.jpg)

Configurez votre Raspberry Pi comme point d'accès de distribution de contenu en utilisant l'installateur Kiwix Hotspot. Cela permet à plusieurs appareils d'accéder au contenu Wikipédia via un réseau local.

**Avantages :**
- Partage de contenu avec plusieurs appareils
- Idéal pour les salles de classe ou les centres communautaires
- Aucune installation individuelle nécessaire sur les appareils clients
- Distribution réseau locale du contenu

## Conseils d'utilisation

Cet ordinateur low-tech est parfait pour :
- Le travail bureautique de base (traitement de texte, tableurs)
- La navigation web (lorsque internet est disponible)
- Les usages éducatifs avec Wikipédia hors ligne
- L'apprentissage de la programmation avec Python (pré-installé)
- La lecture multimédia (vidéos, musique)

## Impact environnemental

En utilisant des périphériques recyclés et un Raspberry Pi à faible consommation, cette configuration :
- Réduit les déchets électroniques
- Consomme très peu d'électricité (< 5W)
- Prolonge la durée de vie du matériel existant
- Coûte une fraction du prix d'un ordinateur neuf

## Informations complémentaires

- **Source :** [Wiki Low-tech Lab](https://wiki.lowtechlab.org/wiki/Ordinateur_low-tech)
- **Licence :** Ce tutoriel est partagé sous licence CC BY-SA (Attribution-Partage dans les Mêmes Conditions)
- **Créateur :** Low-tech Lab
