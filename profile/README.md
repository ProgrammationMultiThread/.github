# Programmation Concurrente en Multi-Threads

Cette organisation contient les ressources et projets liés au cours **Programmation Concurrente en Multi-Threads** de Nantes Université.

---

## Ressources du module

### Cours magistral

- [Slides](https://ProgrammationMultiThread.github.io/CM/PCMT.pdf) : version PDF avec animations
- [Handout](https://ProgrammationMultiThread.github.io/CM/PCMT-handout.pdf) : version PDF sans animation
- [Java-snippets](https://github.com/ProgrammationMultiThread/Java-snippets) : exemples Java du cours
- [Code source](https://github.com/ProgrammationMultiThread/CM) : code LateX des slides

### Travaux dirigés

- [Livret de TD](https://ProgrammationMultiThread.github.io/Exercises/td.pdf) : livret de TD
- [Code source](https://github.com/ProgrammationMultiThread/Exercises) : code LateX du livret d'exercices

### Travaux pratiques

- TP 1 : Introduction à la concurrence
  - [Sujet](https://ProgrammationMultiThread.github.io/Exercises/tp-concurrence.pdf) : version PDF du sujet
  - [Code de base Java](https://github.com/ProgrammationMultiThread/TP-concurrence): code Java à étudier
- TP 2 : Recherche récursive d'expressions régulières sur le Web
  - [Sujet](https://ProgrammationMultiThread.github.io/Exercises/tp-webgrep.pdf) : version PDF du sujet
  - [Code de base Java](https://github.com/ProgrammationMultiThread/TP-webgrep): code Java séquentiel à paralléliser
- TP 3 : Parallélisation de calcul d'image
  - [Sujet](https://ProgrammationMultiThread.github.io/Exercises/tp-mandelbrot.pdf) : version PDF du sujet
  - [Code de base Java](https://github.com/ProgrammationMultiThread/TP-mandelbrot): code Java séquentiel à paralléliser
- TP 4 : Mémoire transactionnelle logicielle
  - [Sujet](https://ProgrammationMultiThread.github.io/Exercises/tp-transactions.pdf) : version PDF du sujet
  - [Code de base Java](https://github.com/ProgrammationMultiThread/TP-transactions): code Java à compléter

---

## Description du module

Ce cours est destiné à des étudiants de M1 en Informatique, ainsi qu'à toute personne s'intéressant à la synchronisation des systèmes répartis.

Le responsable du module est Matthieu Perrin.

Les volumes horaires dédiés à ce cours à Nantes Université (séances de 1h20) sont les suivants :
- Cours magistraux : 12h
- Travaux dirigés : 6.67h
- Travaux pratiques : 5.33h

### Contenu
- Introduction à la concurrence
  - nature des problèmes dans les systèmes à mémoire partagée
  - modèles d’exécution concurrente
  - limites et précautions dans l’usage des threads
- Techniques de synchronisation bloquante
  - verrous
  - moniteurs
  - problèmes de vivacité : interblocage et famine
- Implémentation et modèle mémoire
  - algorithmes de verrous (Peterson, Lamport)
  - modèle mémoire et gestion de la volatilité

### Résultats d'apprentissage
À la fin de ce cours, un étudiant doit être capable de :
- Identifier les possibilités de parallélisation d’un programme.
- Raisonner sur la concurrence et identifier les problèmes d’exécution concurrente.
- Proposer des solutions bloquantes aux problèmes de concurrence.
- Concevoir et implémenter des mécanismes de synchronisation sûrs.
- Développer des applications multi-threads robustes.
- Lire et comprendre la documentation officielle des bibliothèques de gestion de la concurrence.

### Bibliographie
- M. Herlihy & N. Shavit. **The Art of Multiprocessor Programming**, Morgan Kaufmann, 2008.
  > Référence principale sur la programmation concurrente en Java.
- M. Raynal. **Concurrent Programming – Algorithms, Principles, and Foundations**, Springer, 2013.
  > Référence pour les aspects plus algorithmiques du module.

---

## Cours liés

Ce cours a été conçus comme la première partie sur trois d'un cours sur la synchronisation des systèmes répartis : 
- [**Programmation Concurrente en Multi-Thread**](https://github.com/ProgrammationMultiThread) — Programmation multi-threads bloquante en mémoire partagée.
- [**Programmation Distribuée**](https://github.com/AlgorithmiqueConcurrente) — Algorithmique concurrente non-bloquante en mémoire partagée.
- [**Services de Communication et Systèmes Distribués**](https://github.com/DistributedComputing) — Algorithmique tolérante aux pannes en passage de messages.

---

## Licence

Sauf mention contraire, les contenus de cette organisation sont distribués sous les licences suivantes :

- **Supports pédagogiques (LaTeX, transparents, exercices, PDF)** :  
  [Creative Commons Attribution - ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/)
- **Code source Java (snippets, projets de TP)** :  
  [MIT License](https://opensource.org/licenses/MIT)

Les détails, ainsi que les mentions d'attribution, les licences des images et des données externes, sont disponibles dans le fichier [LICENSE.md](https://github.com/ProgrammationMultiThread/.github/blob/main/LICENSE.md).
