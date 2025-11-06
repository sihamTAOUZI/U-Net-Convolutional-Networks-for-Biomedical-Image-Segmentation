# U-Net-Convolutional-Networks-for-Biomedical-Image-Segmentation
# U-Net: Segmentation d'Images Médicales

Ce projet présente une implémentation du modèle **U-Net** pour la segmentation d’images IRM cérébrales. Le U-Net est un réseau de neurones convolutionnels conçu pour attribuer une étiquette à chaque pixel, permettant une localisation précise des zones tumorales.

## Contenu du projet
- Préparation et normalisation des images IRM et de leurs masques.
- Architecture U-Net avec encodeur, bottleneck et décodeur symétrique.
- Entraînement avec l’optimiseur SGD et suivi de la précision et de la perte.
- Visualisation des résultats de segmentation sur le jeu de test.

## Résultats
- Précision finale : 0.9981 (entraînement), 0.9974 (validation)
- Perte finale : 0.0046 (entraînement), 0.0079 (validation)
- Segmentation précise des structures tumorales, même les plus fines.

## Perspectives d’amélioration
- Utilisation d’une fonction de perte basée sur le **Dice coefficient**.
- Expérimentation avec **U-Net++** pour les détails fins.
- Augmentations de données et régularisation pour renforcer la robustesse.
