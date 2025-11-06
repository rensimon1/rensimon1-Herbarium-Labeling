# rensimon1-Herbarium-Labeling
Ce projet vise à automatiser la détection et la lecture des étiquettes présentes sur des images d’herbiers.
L’approche repose sur un modèle YOLOv5 pour la détection des zones d’intérêt et sur des OCR (EasyOCR et TesseractOCR) pour l’extraction du texte.

## Pipeline
1. Récupération des données : téléchargement des images et annotations au format YOLOv5.
2. Détection des étiquettes : entraînement ou utilisation d’un modèle YOLOv5 pré-entraîné (MELU-Trained-ObjDetection-Model-Yolov5-BEST.pt).
3. Pré-traitement : redressement, binarisation, réduction du bruit et ajustement des dimensions.
4. Lecture OCR : extraction du texte avec EasyOCR et TesseractOCR.
5. Évaluation : comparaison des résultats avec la distance de Levenshtein.

## Dataset 
https://online.herbarium.unimelb.edu.au/

## Technologies
Python, YOLOv5, EasyOCR, TesseractOCR, OpenCV, NumPy, Pandas, Matplotlib

## Collaborateurs
GUENNEAU Romain
HASSANI Abdellah
REN Simon
AGNESA Ritchy
