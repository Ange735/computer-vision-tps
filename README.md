# 👁️ Computer Vision : TP et ateliers

Travaux pratiques du module de **Computer Vision** (S6) : traitement d'images avec OpenCV, suivi des mains avec MediaPipe et détection de couleurs en temps réel.

Les notebooks sont **déjà exécutés** : on peut lire les résultats et les images directement sur GitHub, sans rien lancer.

## Notebooks

| # | Notebook | Contenu |
|---|---|---|
| 01 | [Prétraitement avec OpenCV](01_pretraitement_opencv.ipynb) | Chargement d'une image, redimensionnement, rotations, recadrage, découpage en quadrants, flous (moyen, gaussien, médian, bilatéral), netteté, contours Sobel et Canny, mosaïque |
| 02 | [Atelier : manipulation d'images](02_atelier_manipulation_images.ipynb) | L'image vue comme une matrice de pixels, canaux RGB, espaces de couleurs (HSV, YCrCb), seuillage, inversion, modification de pixels et de régions, flips et rotations, filtres (moyenne, Sobel, Laplacien, Canny) |
| 03 | [Lab OpenCV + MediaPipe](03_lab_opencv_mediapipe.ipynb) | Lecture d'image et de webcam, enregistrement vidéo, transformations, contours, histogrammes de couleurs, seuillage adaptatif, segmentation, suivi des mains avec MediaPipe |
| 04 | [Classification de la couleur des citrons](04_classification_couleur_citrons.ipynb) | Détection en temps réel à la webcam : cercles repérés par la transformée de Hough, puis couleur vert ou jaune déterminée dans l'espace HSV |

## Lancer les notebooks

```bash
pip install -r requirements.txt
jupyter notebook
```

Les notebooks 03 et 04 ont besoin d'une webcam. Certaines cellules lisent des images locales (dossier `image/`) qui ne sont pas incluses dans ce dépôt : remplacez-les par vos propres images.

## Technologies

Python · OpenCV · MediaPipe · NumPy · Matplotlib
