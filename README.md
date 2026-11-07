# FACE TO YOU — V1

## Lancer le site
1. Décompressez le dossier.
2. Ouvrez `index.html` dans un navigateur, ou ouvrez le dossier dans Visual Studio Code.
3. Pour une expérience locale plus fiable, lancez un serveur de développement (par exemple l'extension Live Server de VS Code).

## Fonctionnalités incluses
- Site responsive ordinateur / tablette / téléphone.
- Accueil et navigation.
- Questionnaire 1 (30 questions, réponses à choix et questions ouvertes facultatives).
- Questionnaire 2 (10 questions ouvertes), accessible après le premier bilan.
- Barre de progression et sauvegarde locale des réponses.
- Bilan indicatif personnalisé avec cinq domaines, points d'appui et pistes de réflexion.
- Journal personnel local avec suppression des entrées.
- Objectifs avec cases de suivi.
- Historique local des bilans.
- Profil local facultatif.
- Impression du bilan.
- Animations de boutons, transitions et respect de `prefers-reduced-motion`.

## Limites importantes de cette V1
- Les données restent dans le stockage local du navigateur (`localStorage`). Elles ne sont pas synchronisées entre appareils.
- Le compte en ligne et la base de données distante ne sont pas encore connectés.
- Le bilan est un outil de réflexion non médical. Les pourcentages sont des indicateurs descriptifs simplifiés, pas des scores psychologiques validés.
- La police distante peut nécessiter une connexion internet ; des polices de secours sont prévues.

## Structure
- `index.html` : pages et structure.
- `styles.css` : identité visuelle et responsive design.
- `app.js` : navigation, questionnaires, calcul du bilan, journal et objectifs.
- `assets/angel-art.jpg` : visuel d'ambiance (si disponible).
