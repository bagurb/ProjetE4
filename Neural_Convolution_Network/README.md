# PROJET_E4 - Neural Convolution Network pour analyse d'ECG_Audio.

Ce modèle a pour but de donner un premier diagnostique d'ECG à partir de fichier audio. Il s'inscrit dans un projet de deuxième année d'école d'ingénieur à ESIEE Paris, le projet R25 - Suivi de grossesses en zone rurales au Burkina Faso, en Australie et au Timor oriental, année 2021 - 2022, dans le cadre duquel doit être réalisé un stéthoscope connecté afin de faciliter l'intervention des médecins dans des zones rurales. 

## Installation

Installation des imports :

Entrez la commande suivante dans un terminal situé dans le dossier root (Neural_Convolution_Network) du projet.
```
pip install -r requirements.txt
```

Le script ce trouve dans le notebook spectrogram_Categorization.ipynb.
Exécutez les cellules une par une.

## Architecture

* Data : contient les données format .wav (MLDataset) et leurs spectrogrames format .png (Spectrograms)
* prediction_results.csv : les résultats de prédiction du modèle
* requirements.txt : fichier d'installation des imports
* spectrogram_Categorization.ipyng : notebook principal contenant le traitement des données et le modèle

### Tâches effectuées
* Écriture du code pour le modèle avec la librairie Keras.
* Organisation et séparation des données pour les train_set, test_set.

### Problèmes

* Le modèle reconnaît tous les spectrogrammes comme des spectrogrammes d’individus témoins.
* Problème dans la catégorisation des spectrogrammes.

### Solutions

* Problème dans le modèle au niveau des layers?
* Base de données trop petite, une augmentation des données?
* Duplication des données? (risque de biaiser l’IA)
* Changer la base de données?
* Changer de modèle?
