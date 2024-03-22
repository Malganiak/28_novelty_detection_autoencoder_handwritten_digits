# 28_novelty_detection_autoencoder_handwritten_digits

Détection de Nouveautés, Autoencodeur et Chiffres Manuscrits.

Introduction
Ce projet vise à comprendre, décrire et mettre en œuvre les concepts de détection de nouveautés à l'aide d'autoencodeurs, avec une application spécifique à la détection de chiffres manuscrits.

Contexte du Projet
Par le passé, nous avons développé une application de vision par ordinateur capable de reconnaître des chiffres manuscrits. Cependant, les performances de notre application sont compromises par des perturbations extérieures sur les images capturées. L'objectif de ce projet est d'améliorer la reconnaissance de chiffres manuscrits en utilisant la détection d'anomalies.

NB : Il est important de ne pas utiliser de Denoising Autoencoder ni de Variational Autoencoder.

Livrables

Création d'une base d'images comprenant idéalement 10 000 images de 28 par 28 pixels en noir et blanc. Ces images doivent représenter divers types d'objets, à l'exception des chiffres manuscrits, formant ainsi un ensemble de tests d'anomalies/nouveautés. L'autre partie du jeu de test sera constituée des 10 000 images du jeu de test de la MNIST.
Mise en place d'un Jupyter Notebook implémentant un autoencodeur (Fully Connected, éventuellement Convolutionnel selon vos préférences) entraîné en mode OneClass sur le jeu d'apprentissage de la MNIST.
Pour les participants les plus avancés, utilisez la partie décodeur de l'autoencodeur entraîné pour générer des images synthétiques de chiffres manuscrits. Cela servira d'introduction aux modèles génératifs.
Critères de Performance
L'objectif est d'atteindre une précision maximale (accuracy) dans la détection de nouveautés, en mettant particulièrement l'accent sur l'amélioration des performances de reconnaissance de chiffres manuscrits dans notre application.
