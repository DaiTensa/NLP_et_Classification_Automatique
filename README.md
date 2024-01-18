# Projet 6 : NLP et Classification Automatique

# Présentation du projet

Dans ce projet, une plate-forme de e-commerce envisage de lancer une marketplace, sur laquelle des vendeurs proposent des produits en postant une photo et une description.

L'attribution de la catégorie d'un produit donné s'effectue manuellement par les vendeurs.
Afin de faciliter l'expérience utilisateur des vendeurs et des acheteurs, et dans l'optique d'augmentation de nombre de produits, il devient nécessaire d'automatiser l'attribution d'une catégorie en analysant automatiquement la description d'un produit donné.

Nous étudierons  donc la faisabilité d'un moteur de classification des produits en différentes catégories.

# Mission

- Étude de faisabilité d'un moteur de classification.
- Analyser les descriptions textuelles et les images des produits.
- Prétraitement des données textes et images et extraction de features.
- Réduction à 2 dimensions à l'aide d'une **ACP** ou **t-SNE**.

![tsne](https://github.com/DaiTensa/NLP_et_Classification_Automatique/blob/main/figures/TSNE_Kmean_1.png?raw=true)

- Réaliser une mesure de similarité **ARI** entre les catégories.
- Mettre en place deux approche de type **bag-of-words** et comptage simple **tTf-Idf**.
- Une approche de type **word/sentence embedding** exemple avec **Word2Vec**, **Glove** ou **FastText**.
- **BERT**, **USE**.
- Concernant les features images, mettre en place un algorithme **SIFT** et un autre de type transfer learning **CNN**.

**L'extraction de features**: également appelée "extraction de caractéristiques" ou "réduction de dimensionnalité", est une étape importante dans la préparation des données pour l'apprentissage automatique ou l'analyse de données. Elle consiste à sélectionner les caractéristiques les plus importantes ou les plus pertinentes du jeu de données et à les extraire dans un format adapté à l'analyse.

![features](https://github.com/DaiTensa/NLP_et_Classification_Automatique/blob/main/figures/Features_exemple_1.png?raw=true)

# Compétences

- Prétraitements de données Texte et Images.
- Représentation graphique et réductions de dimensions.
- Techniques de réduction de dimension t-SNE, ACP.
- Stratégie de collecte de données.
- Élaboration d'un modèle d'apprentissage profond.
- Évaluation de la performance d'un modèle d'apprentissage profond.
- Augmentation des données.

# Source de données

[Les données images : lien pour télécharger - fichier zip](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Textimage+DAS+V2/Dataset+projet+pre%CC%81traitement+textes+images.zip)