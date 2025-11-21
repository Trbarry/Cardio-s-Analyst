# 🏃‍♂️ Cardio Analyst V3

![Status](https://img.shields.io/badge/Status-Functional-success)
![Tech](https://img.shields.io/badge/Stack-Vanilla%20JS%20%7C%20HTML5%20%7C%20CSS3-blueviolet)
![Privacy](https://img.shields.io/badge/Privacy-Local%20Client--Side-green)

Un outil web léger et autonome ("Single File Component") conçu pour analyser les exports de données d'entraînement et simuler l'impact de l'inclinaison sur la dépense énergétique.

Conçu pour transformer des données brutes (CSV) en métriques visuelles concrètes (Tours Eiffel grimpées, Tours de stade, etc.) sans envoyer de données sur un serveur tiers.

##  Fonctionnalités Clés

- **Parsing CSV Intelligent** : Algorithme capable de lire des fichiers d'export Excel complexes (détection automatique des colonnes, nettoyage des erreurs `#DIV/0!`, formatage des dates).
- **Simulation Physique** : Moteur de calcul en temps réel. Permet d'appliquer une pente virtuelle (%) sur des pas réalisés à plat pour estimer l'effort métabolique équivalent.
- **Data Visualization** :
  - Tableau de bord KPI (Pas réels vs Pas d'effort).
  - Gamification (Comparaison avec la hauteur de la Tour Eiffel, du Mont Blanc, etc.).
- **Privacy First** : Architecture 100% Client-Side via l'API `FileReader`. Aucune donnée ne quitte le navigateur de l'utilisateur.
- **UI/UX** : Interface "Dark Mode" responsive, inspirée des dashboards d'administration système.

##  Stack Technique

Ce projet est réalisé sans dépendances lourdes (No Framework) pour garantir performance et portabilité.

- **Core** : JavaScript (ES6+) pour la logique de calcul et le parsing.
- **DOM** : Manipulation native pour la génération dynamique du tableau.
- **Style** : CSS3 avec variables CSS (Custom Properties) pour la gestion du thème.

##  Installation & Usage

Aucune installation (`npm install`) n'est nécessaire. C'est une application portable.

### En local
1. Clonez le dépôt :
   ```bash
   git clone [https://github.com/TON_USER/cardio-analyst.git](https://github.com/TON_USER/cardio-analyst.git)
