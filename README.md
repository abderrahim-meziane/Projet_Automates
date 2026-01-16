# 🤖 Manipulation d'Automates Finis — Sorbonne Université (LU2IN005)

Ce projet implémente une bibliothèque Python complète pour la manipulation d'**automates finis** (déterministes, non-déterministes, complets). Il a été réalisé dans le cadre de l'unité d'enseignement **Mathématiques discrètes (LU2IN005)**.

## 📋 Présentation du Projet
L'objectif est de fournir des outils pour construire, transformer et combiner des automates afin d'étudier les langages formels. Le projet utilise une structure modulaire séparant les composants de l'automate (États, Transitions) de la logique algorithmique.

## ⚙️ Algorithmes Implémentés
Le fichier principal `Projet_automates.ipynb` contient les implémentations suivantes :

* **Opérations de base** : Création depuis un fichier texte, complétion d'automates.
* **Déterminisation** : Passage d'un AFN (Automate Fini Non-déterministe) à un AFD (Déterministe).
* **Opérations Rationnelles** :
    * Union
    * Concaténation
    * Étoile de Kleene
* **Opérations Ensemblistes** :
    * Intersection
    * Complémentaire
