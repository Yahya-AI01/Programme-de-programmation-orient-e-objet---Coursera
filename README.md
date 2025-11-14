# Projets de Programmation Orientée Objet - Coursera

Ce repository contient une série de projets C++ réalisés dans le cadre du cours de Programmation Orientée Objet sur Coursera. Chaque projet correspond à une semaine de cours et met en œuvre des concepts spécifiques de la POO en C++.

## 📁 Structure des Projets

Le repository est organisé en fichiers séparés, chaque fichier représentant un projet complet :

### 🏴‍☠️ **bateaux.cc** - Système de combat naval
- **Concepts** : Héritage multiple, classes abstraites, polymorphisme
- **Classes principales** : `Navire`, `Pirate`, `Marchand`, `Felon`
- **Fonctionnalités** : Simulation de combats entre différents types de navires avec comportements spécifiques

### 📚 **biblio.cc** - Système de gestion de bibliothèque
- **Concepts** : Composition, gestion de mémoire, destructeurs
- **Classes principales** : `Auteur`, `Oeuvre`, `Exemplaire`, `Bibliotheque`
- **Fonctionnalités** : Gestion de collections de livres avec auteurs et exemplaires

### 🧪 **chimie.cc** - Simulation de mélanges chimiques
- **Concepts** : Surcharge d'opérateurs, amis de classe
- **Classes principales** : `Flacon`
- **Fonctionnalités** : Calcul automatique du pH lors du mélange de solutions

### 🏗️ **construction.cc** - Système de construction 3D
- **Concepts** : Surcharge d'opérateurs avancée, matrices 3D
- **Classes principales** : `Brique`, `Construction`
- **Fonctionnalités** : Construction d'objets 3D avec opérations d'assemblage

### 🐉 **dragons.cc** - Système de combat de créatures
- **Concepts** : Héritage, méthodes virtuelles, combat tour par tour
- **Classes principales** : `Creature`, `Dragon`, `Hydre`
- **Fonctionnalités** : Simulation de combats entre différentes créatures

### ⚖️ **imc.cc** - Calculateur d'IMC
- **Concepts** : Classes simples, encapsulation
- **Classes principales** : `Patient`
- **Fonctionnalités** : Calcul de l'Indice de Masse Corporelle

### 🐭 **labo.cc** - Simulation de souris de laboratoire
- **Concepts** : Constructeurs/destructeurs, clonage, vieillissement
- **Classes principales** : `Souris`
- **Fonctionnalités** : Simulation du cycle de vie de souris avec clonage

### 🍳 **restaurant.cc** - Système de recettes culinaires
- **Concepts** : Héritage complexe, composition récursive, design pattern Composite
- **Classes principales** : `Produit`, `Ingredient`, `Recette`, `ProduitCuisine`
- **Fonctionnalités** : Gestion hiérarchique de recettes avec adaptation des quantités

### 💌 **timbres.cc** - Système de collection de timbres
- **Concepts** : Héritage, calcul de valeur, classes dérivées
- **Classes principales** : `Timbre`, `Rare`, `Commemoratif`
- **Fonctionnalités** : Évaluation de la valeur des timbres selon leur rareté

### 🐖 **tirelire.cc** - Gestionnaire d'épargne
- **Concepts** : Classes simples, méthodes constantes
- **Classes principales** : `Tirelire`
- **Fonctionnalités** : Gestion basique d'une tirelire électronique

## 🛠️ Compilation et Exécution

Pour compiler et exécuter un projet spécifique :

```bash
g++ -std=c++11 -o projet nom_du_fichier.cc
./projet
