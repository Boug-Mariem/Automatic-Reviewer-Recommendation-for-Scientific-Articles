# Reviewer Recommendation System for Arabic Scientific Articles

## Project Objective

Ce projet a pour objectif de recommander automatiquement des reviewers pour des articles scientifiques en langue arabe en utilisant des techniques d’apprentissage automatique et de traitement du langage naturel (NLP).

Le système analyse le contenu des articles et propose des reviewers pertinents en fonction de la similarité sémantique et des caractéristiques extraites.

---

## Notebook

Le code est fourni sous forme de notebook Jupyter (.ipynb) et peut être exécuté :
- sur Google Colab
- ou en local (Jupyter Notebook)

ien Google Colab :  
https://colab.research.google.com/drive/1SarUfRkUMiMDXWQSdtbP8Hw8YAMLmqE0?usp=sharing

---

## Structure du projet
data/
│
├── All_Articles_Combined(Sheet1).csv
│ → Dataset principal contenant les articles scientifiques et leurs attributs
│
├── arabic_stopwords.txt
│ → Liste des mots vides en arabe utilisée pour le prétraitement

sortie/
│
→ Contient les données générées à chaque étape du pipeline :
- données prétraitées
- tokenisation
- matrices TF-IDF
- encodage
- résultats intermédiaires
- modèles entraînés


---

## Instructions d’exécution

### 1. Ouvrir le notebook
Ouvrir le fichier `.ipynb` dans Google Colab ou en local.

---

### 2. Préparer les données
Placer les fichiers suivants dans le dossier `data/` :
- All_Articles_Combined(Sheet1).csv
- arabic_stopwords.txt

---

### 3. Installation des dépendances
Toutes les bibliothèques nécessaires sont installées automatiquement dans Google Colab.

---

### 4. Exécution
Exécuter toutes les cellules du notebook dans l’ordre.

Étapes du pipeline :
- Prétraitement du texte
- Nettoyage des données
- Tokenisation
- Vectorisation TF-IDF
- Encodage des données
- Entraînement du modèle
- Génération des recommandations

---

### 5. Résultats
Les résultats sont :
- affichés dans le notebook
- sauvegardés dans le dossier `sortie/`

---

## Collaborateurs

- Mareim boughizene 
- Mohsen Allani

---

## Remarque

Ce projet est un travail expérimental visant à appliquer des techniques de NLP et de machine learning sur des articles scientifiques en langue arabe.
