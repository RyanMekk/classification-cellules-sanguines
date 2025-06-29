# Classification de cellules sanguines à partir d’images microscopiques

## Contexte

Projet universitaire réalisé dans le cadre du cours **Sciences des Données 4** (Université Paul Valéry, Montpellier 3).

Objectif : développer des modèles de machine learning et deep learning pour classifier des images de globules blancs en quatre classes :
- éosinophiles
- lymphocytes
- monocytes
- neutrophiles

## Données utilisées

- Jeu de données public Kaggle : [Blood Cell Images](https://www.kaggle.com/datasets/paultimothymooney/blood-cells)

## Outils et modèles

- Python
- PyTorch
- CNN personnalisé
- ResNet18 pré-entraîné
- MLP
- Classificateurs traditionnels : k-NN, SVM, Random Forest
- Data augmentation (torchvision.transforms)

## Résultats clés

- CNN → précision test : **84,76 %**
- ResNet18 → précision test : **85,65 %**
- MLP → précision test : **25 %**
- Les classificateurs Random Forest et SVM ont permis d’explorer les représentations extraites des modèles profonds.

## Auteurs

- Ryan Mekki
- Maïmouna Coulibaly

## Démonstration vidéo

[Vidéo de présentation du projet](https://pod.univ-montp3.fr/media/videos/9c51dbf59cb2bb2a34d7b1c38016a3a9ca545355e3f8e99fb831f8da453c0bf3/projet_final.mp4)
