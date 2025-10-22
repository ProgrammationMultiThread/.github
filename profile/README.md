# Programmation Concurrente en Multi-Threads

Cette organisation contient les ressources et projets liés au cours **Programmation Concurrente en Multi-Threads** de Nantes Université.

## Dépôts principaux

- [**CM**](https://github.com/ProgrammationMultiThread/CM) — Slides de cours.
  - [Slides](https://ProgrammationMultiThread.github.io/CM/PCMT.pdf): version PDF avec animations
  - [Handout](https://ProgrammationMultiThread.github.io/CM/PCMT-handout.pdf): version PDF sans animation
- [**TD**](https://github.com/ProgrammationMultiThread/TD) — Exercices de TD.
  - Dépôt en construction : cette ressource n'est pas encore disponible.
- [**TP**](https://github.com/ProgrammationMultiThread/TP) — Exercices de TP.
  - Dépôt en construction : cette ressource n'est pas encore disponible.

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

## Cours liés
Ce cours a été conçus comme la première partie sur trois d'un cours sur la synchronisation des systèmes répartis : 
- [**Programmation Concurrente en Multi-Thread**](https://github.com/ProgrammationMultiThread) — Programmation multi-threads bloquante en mémoire partagée.
- [**Programmation Distribuée**](https://github.com/AlgorithmiqueConcurrente) — Algorithmique concurrente non-bloquante en mémoire partagée.
- [**Services de Communication et Systèmes Distribués**](https://github.com/DistributedComputing) — Algorithmique tolérante aux pannes en passage de messages.

## Licence
Sauf mention contraire, les contenus sont sous licence
- [Creative Commons Attribution - ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) pour les sources LaTeX.
- [MIT](https://opensource.org/licenses/MIT) pour les projets Java.
