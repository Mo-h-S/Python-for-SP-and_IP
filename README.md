
<<<<<<< HEAD
# Signal and Image Processing with Python

## Introduction

Welcome to this repository! This repo contains a basic starting guide for using Python to perform signal and image processing. Whether you're new to this field or looking for a refresher, you'll find essential tools and examples to help you get started.

## Getting Started

The first folder contains installation guide to setup the envirenement work to have the essential tools to perform the needed taskes.

## Contents
- Introduction to Python
- An installation guide of Python on diferent operating systems 
- Lazy guide to setup the envirenement work
- Configration of the IDLE (Spdeyr)
- Managing Envirements

  ### libraries for data manipulation
   - NumPy / Pandas
   - Matplotlib
  ### library for signal processing
   - SciPy
  ### libraries for Image processing
   - Scikit-image
   - OpenCV

- In addition to examples of:
- Signal Processing
  - Generating and analyzing signals
  - Fourier transforms
- Image Processing
  - Reading and displaying images
  - Basic image transformations (grayscale conversion, blurring)

1. **Installation**: Ensure you have Python and the necessary libraries installed. The primary libraries used are:


2. **Setup**: Clone this repository to your local machine using:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
Navigate to the project directory:

bash

Copier
cd your-repo-name

## Contents
1. **libraries**:  The second  folder contains the essential libraries to perform the needed processing.
**/!\/**: Ensure you have Python and the necessary libraries installed (see link). 
The primary libraries used are:
  ### libraries for data manipulation
   - NumPy / Pandas
   - Matplotlib
  ### library for signal processing
   - SciPy
  ### libraries for Image processing
   - Scikit-image
   - OpenCV

2. **Examples**: In addition to examples of:
- Signal Processing
  - Generating and analyzing signals
  - Fourier transforms
- Image Processing
  - Reading and displaying images
  - Basic image transformations (grayscale conversion, blurring)

=======
# Python pour le TS et le TI

## Qu'est-ce que Python ?

Python est un langage de programmation polyvalent, créé par Guido van Rossum. Il est connu pour sa syntaxe claire et sa facilité d'utilisation, ce qui en fait un choix populaire pour les débutants et les professionnels.

## Utilisateurs de Python

Python est utilisé dans divers domaines, notamment :
* Développement logiciel
* Science des données
* Administration système
* Développement web
* Recherche académique

Des entreprises comme Netflix, Spotify et NASA utilisent Python pour diverses applications.

* Avantages de Python
* Facile à apprendre
* Bibliothèques étendues
* Multiplateforme
* Fort soutien communautaire

## Prérequis pour l'installation
- Connaissances informatiques de base Familiarité avec la ligne de commande  
- Ordinateur avec connexion Internet
- Système d'exploitation compatible (Windows 7+, macOS 10.9+, ou Linux)
- Au moins 4 Go de RAM et 5 Go d'espace disque1

## Deux choix pour installer Python sur votre système.

#### Installation de Python sur différents systèmes et un IDLE
Télécharger le programme d'installation depuis le site officiel de Python 
| Système   | Lien      | 
| :-------  | :-------  | 
| Windows  | https://www.python.org/downloads/windows/  |
| Ubuntu | https://www.python.org/downloads/source/  | 
| MacOS | https://www.python.org/downloads/macos/  | 


Exécuter le programme d'installation
Personnaliser l'installation (facultatif)
Lancer l'installation
Vérifier l'installation via la commande python --version
Une alternative est d'installer Python via le Microsoft Store

### IDLE : Environnement de Développement Intégré
IDLE (Integrated Development and Learning Environment) est l'environnement de développement intégré pour Python, conçu pour faciliter l'apprentissage et le développement. Il est entièrement écrit en Python et fonctionne sur plusieurs plateformes, y compris Windows, Unix et macOS.
#### Fonctionnalités Principales
- Console Interactive : Permet d'exécuter du code Python ligne par ligne avec coloration syntaxique pour une meilleure lisibilité.
- Éditeur de Texte : Offre des fonctionnalités avancées comme l'auto-complétion, l'indentation automatique et la gestion des erreurs.
- Outils de Débogage : Inclut des options pour définir des points d'arrêt et inspecter les variables.
- Gestion des Fichiers : Facilite la création, l'ouverture et la sauvegarde de scripts Python.
- Documentation Intégrée : Accès direct à la documentation Python pour aider les utilisateurs à comprendre les fonctionnalités.
IDLE est particulièrement adapté aux débutants en raison de son interface intuitive, mais il peut être limité pour des projets plus complexes, où d'autres IDE comme VSCode ou PyCharm pourraient être plus appropriés.


## Facilite la vie en installant Anaconda pour avoir tous les packages

#### Installation python avec Anaconda

Anaconda est une distribution logicielle gratuite et facile à installer pour Python et R, qui comprend une vaste collection de plus de 7 500 packages open source (incluant R)14. Lors de l'installation d'Anaconda, plus de 250 packages sont automatiquement installés en même temps que Python.

## Installation d'anaconda sur différents systèmes
Télécharger le programme d'installation depuis le site officiel d'anaconda

| Système   | Lien      | 
| :-------  | :-------  | 
| Windows  | https://repo.anaconda.com/archive/Anaconda3-2024.10-1-Windows-x86_64.exe  |
| Ubuntu | :https://repo.anaconda.com/archive/Anaconda3-2024.10-1-Linux-x86_64.sh  | 
| MacOS | https://repo.anaconda.com/archive/Anaconda3-2024.10-1-MacOSX-arm64.pkg  | 

Ouvrir Anaconda Navigator : Lancez Anaconda Navigator depuis le menu de votre système d'exploitation ou en utilisant le terminal avec la commande anaconda-navigator.

- Lancer Spyder : Dans Anaconda Navigator, cliquez sur l'icône de Spyder pour l'ouvrir / Vous pouvez également lancer Spyder directement depuis le terminal(anaconda prompt) en tapant spyder.

  Et voila !!!!!

## Avant de commencer

### Configuration de spyder 

#### Configuration de la sortie graphique
Ouvrez Spyder.
- Allez dans le menu Outils.
- Sélectionnez Préférences.
- Dans la fenêtre des préférences, allez dans IPython console > Graphiques (Choisissez graphique) et vous pouvez configurer la sortie graphique selon vos besoins (par exemple, choisir entre une sortie inline ou une nouvelle fenêtre).

##### Effacer les variables avant l'exécution
- Allez dans Console d'IPython > Exécution.
- Cochez l'option Effacer toutes les variables avant de démarrer une exécution.

##### Configuration de l'aide dans les préférences
- Allez dans Aide. 
- Ici, vous pouvez configurer comment vous souhaitez que l'aide s'affiche (par exemple, en ligne, dans une fenêtre séparée, etc.).
- Cochez toutes les cases.

#### Indentation automatique
Allez dans Préférences.
- Sous Editeur > Indentation, vous pouvez configurer l'indentation automatique. Vous pouvez choisir entre des tabulations ou des espaces et définir le nombre d'espaces par indentation.
- Pour respecter la PEP8
- Sélectionnez Utiliser des espaces au lieu des tabulations, car PEP8 recommande d'utiliser 4 espaces pour chaque niveau d'indentation.
- Définissez le nombre d'espaces par indentation à 4.

## Pour commencer

- Configurer votre projet : Une fois Spyder ouvert, allez dans le menu "Projets" et créez un nouveau projet
- Donnez un nom à votre projet et choisissez un répertoire pour le stocker
- Écrire et exécuter du code : Utilisez l'éditeur de texte de Spyder pour écrire votre code Python
- Par exemple, vous pouvez écrire un simple script comme print("Hello, World!")
- Pour exécuter le script, cliquez sur le bouton "Exécuter" dans la barre d'outils ou utilisez le raccourci clavier Ctrl + Entrée
- Explorer les variables : Utilisez l'Explorateur de Variables pour voir les valeurs de vos variables pendant l'exécution de votre programme
- Vous pouvez trouver cet outil dans l'onglet "Variables" à droite de l'interface
- Accéder à la documentation : Pour obtenir la documentation d'une fonction ou d'un module, placez simplement le curseur sur le nom de la fonction ou du module et appuyez sur la touche F11
>>>>>>> 7b9d06b43f7f3832551353cd22282ae894c5b65e

## Feedback

If you have any feedback, please reach out to us.

## Sources 

https://www.anaconda.com/download/success

https://www.python.org/downloads/
