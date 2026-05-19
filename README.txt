Ce projet a pour objectif de recommander des reviewers pour des articles scientifiques en langue arabe à l’aide de techniques d’apprentissage automatique.
Le code est fourni sous forme de notebook (.ipynb) et peut être exécuté directement dans Google Colab pour plus de simplicité.
lien collab: 
https://colab.research.google.com/drive/1SarUfRkUMiMDXWQSdtbP8Hw8YAMLmqE0?usp=sharing

Le dossier projets excels contient :

- data/ :
All_Articles_Combined(Sheet1).csv – fichier principal contenant les articles et leurs attributs.
arabic_stopwords.txt – liste des mots vides arabes pour le prétraitement du texte.
- sortie/ :
Contient toutes les formes de données générées au cours du projet (après prétraitement, tokenisation, TF-IDF, encodage, etc.) que vous pouvez consulter pour analyse.


Instructions pour l’exécution:
- Ouvrir le notebook  dans Google Colab ou localement.
- Placer les fichiers All_Articles_Combined(Sheet1).csv et arabic_stopwords.txt dans le sous-dossier data.
Tous les packages Python nécessaires seront installés automatiquement si vous exécutez le notebook dans Colab.
- Exécuter toutes les cellules du notebook.
Les résultats générés (matrices TF-IDF, données prétraitées, scores, modèles entraînés, etc.) apparaîtront et seront également enregistrés dans le dossier sortie.