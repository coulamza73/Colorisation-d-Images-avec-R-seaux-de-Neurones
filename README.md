# Colorisation-d-Images-avec-R-seaux-de-Neurones
Ce projet explore l’utilisation du Deep Learning pour la colorisation automatique d’images en noir et blanc, en s’appuyant sur des architectures avancées de réseaux de neurones. L’objectif est de reconstruire des couleurs réalistes en apprenant les relations entre les niveaux de gris et les teintes naturelles des objets.
Déroulement du projet :
•	Préparation des données : Utilisation du dataset Fashion MNIST, conversion des images en niveaux de gris et normalisation des pixels pour optimiser l’apprentissage.
•	Conception du modèle : Mise en place d’un réseau de type encodeur-décodeur avec des couches de convolution et des UpSampling2D pour reconstruire les images en couleur.
•	Utilisation de modèles pré-entraînés : Intégration de ResNet50 pour extraire des caractéristiques complexes et améliorer la qualité des images colorisées.
•	Entraînement et optimisation : Ajustement des hyperparamètres, utilisation de la fonction de perte perceptuelle et évaluation des performances à l’aide de métriques adaptées.
Applications :
Ce projet peut être appliqué à la restauration d’anciennes photographies, à la génération d’images artistiques ou à l’amélioration de la vision par ordinateur pour des tâches de reconnaissance d’objets.

