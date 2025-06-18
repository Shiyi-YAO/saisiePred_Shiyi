# Modèle de la saisie prédictible du portable (SMS)

## Description

Ce projet implémente deux prédictions de texte courantes basées sur Python pour améliorer l'expérience de saisie sur les appareils mobiles :

1. **Complétion de mots (Trie)** - Suggère des complétions possibles pour les mots partiellement saisis
2. **Prédiction du mot suivant (N-gram)** - Prédit le prochain mot le plus probable basé sur le contexte

## Fonctionnalités

### 1. Complétion de mots (Trie)
- Structure de données Trie optimisée pour la recherche rapide
- Suggestions de complétion basées sur les préfixes
- Support des mots fréquents du corpus SMS

### 2. Prédiction N-gram
- Modèle statistique pour prédire le mot suivant
- Basé sur l'analyse des séquences de mots dans le corpus
- Support des bigrammes et trigrammes

## Setup

### Exigences
1. **Python 3.7+**: Assurez-vous d'avoir installé Python 3.7 ou supérieur.

### Installation
1. Ouvrir ce ficher(SaisivePredictive) dans terminal (pour MacOS et Windows)

2. Install the required Python packages:

   MacOS
   ```bash
   pip3 install pandas scikit-learn matplotlib nltk openpyxl
   ```
   Windows
   ```bash
   pip install pandas scikit-learn matplotlib nltk openpyxl
   ```
### Exécution

1. Vous pouvez commencer à expérimenter notre modèle !
   
   MacOS
   ```bash
   python3 main.py
   ```
   Windows
   ```bash
   py main.py
   ```

2. Si vous voulez tester notre programme : 
- test de n-gram
  
   MacOS
   ```bash
   python3 -m ngramme.test_ngramme
   ```
   Windows
   ```bash
   py -m ngramme.test_ngramme
   ```
- test du tri

   MacOS
   ```bash
   python3 -m trie.test_trie
   ```
   Windows
   ```bash
   py -m trie.test_trie
   ```
  

## Référence :
   ```bash
   https://github.com/Shubhamsaboo/awesome-llm-apps/blob/main/starter_ai_agents/ai_blog_to_podcast_agent/README.md?plain=1
   ```
