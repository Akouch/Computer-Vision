# Computer-Vision
=========================================================
DATASET : Projet Computer Vision - Restauration de Plaques
=========================================================

1. DESCRIPTION DU JEU DE DONNÉES
Ce dossier contient les images utilisées pour tester et valider l'algorithme de défloutage aveugle (Blind Deblurring) via l'analyse Cepstrale et le filtre de Wiener.

2. CONTENU DU DOSSIER
- Images originales (ex: plaque_1.jpg à plaque_6.jpg) : Plaques d'immatriculation nettes utilisées comme "Vérité Terrain" (Ground Truth) pour la simulation numérique du flou.
- Images floues (le cas échéant) : Images dégradées par un flou de mouvement rectiligne destinées à être réparées par l'interface Gradio.

3. ORIGINE DES DONNÉES
Ces images représentent des plaques d'immatriculation au format standard (notamment marocaines) et ont été sélectionnées pour leur diversité de contraste et de luminosité afin de tester la robustesse du filtre de Wiener et l'apparition du Ringing Effect.

4. UTILISATION
Pour utiliser ce dataset avec le Notebook fourni :
- Importez ces images dans l'environnement d'exécution (ex: Google Colab).
- Glissez-déposez l'une de ces images dans l'interface web Gradio générée par le code pour observer le diagnostic spectral et la restauration.
