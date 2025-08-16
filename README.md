# Système de Résumé Automatique de Texte

Ce projet est un système de résumé de texte automatique utilisant Python, Hugging Face Transformers, et spaCy.

## Étapes de Réalisation du Projet

1.  **Configuration de l'environnement**
    *   Créer un environnement virtuel Python.
    *   Installer les bibliothèques nécessaires : `transformers`, `torch`, `spacy`, etc. (`pip install -r requirements.txt`).
    *   Télécharger les modèles linguistiques pour spaCy (`python -m spacy download fr_core_news_sm`).

2.  **Prétraitement du Texte**
    *   Nettoyage du texte source (si nécessaire).
    *   Utilisation de spaCy pour la segmentation en phrases.

3.  **Modèle de Résumé**
    *   Charger un modèle pré-entraîné de Hugging Face (par exemple, BART ou T5).
    *   Utiliser le pipeline de résumé de Transformers.

4.  **Développement du Script Principal**
    *   Créer un script Python qui prend un texte en entrée.
    *   Le script traite le texte et utilise le modèle pour générer un résumé.
    *   Afficher le résumé en sortie.

5.  **Interface Utilisateur (Optionnel)**
    *   Créer une interface web simple avec Flask ou Streamlit pour une utilisation interactive.

6.  **Tests**
    *   Écrire des tests unitaires pour valider la logique de résumé.
