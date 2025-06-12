# Modèle de la saisie prédictible du portable (SMS)

## Description

Ce projet implémente deux prédictions de texte courantes basées sur Python pour améliorer l'expérience de saisie sur les appareils mobiles :

1. **Complétion de mots (Trie)** - Suggère des complétions possibles pour les mots partiellement saisis
2. **Prédiction du mot suivant (N-gram)** - Prédit le prochain mot le plus probable basé sur le contexte

## Structure du projet

```
text/
├── models/                     // stocke les modèles
│   ├── __pycache__/           // caches Python
│   ├── ngram.py               // implémentation du modèle n-gram
│   └── trie.py                // implémentation du Trie
├── 88milSMS_88522.xlsx        // corpus SMS d'origine
├── interface.py               // interface CLI interactive
├── main.py                    // script d'entrée principal
├── utils.py                   // fonctions utilitaires (chargement, prétraitement)
├── ngram_test.py              // tests unitaires du modèle n-gram
├── trie_test.py               // tests unitaires du Trie
└── README.md                  // documentation (ce fichier)
```

## Fonctionnalités

### 1. Complétion de mots (Trie)
- Structure de données Trie optimisée pour la recherche rapide
- Suggestions de complétion basées sur les préfixes
- Support des mots fréquents du corpus SMS

### 2. Prédiction N-gram
- Modèle statistique pour prédire le mot suivant
- Basé sur l'analyse des séquences de mots dans le corpus
- Support des bigrammes et trigrammes

## Installation
- git clone 

### Prérequis
- Python 3.7 ou supérieur
