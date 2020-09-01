| [Accueil](index.md) | [Notes de cours](notes-de-cours.md) | [TPs](travaux-pratiques.md) | [Projet Final](projet-final.md) | [Plan de cours](plan-de-cours.md) |

# Introduction à l’apprentissage automatique (ML) PolyAI - Automne 2020

Ce cours est une introduction aux algorithmes d'apprentissage, un champ de recherche en intelligence artificielle. Ces algorithmes ont pour objectif de permettre à la machine d'apprendre à partir d'exemples. Ce cours se concentre plus sur l’intuition et les applications pratiques du ML, et moins sur la théorie pure (et donc, moins de maths que d’habitude). Ce cours est aussi conçu plus pour les personnes qui ne veulent pas devenir chercheur en ML, mais ont plutôt besoin des techniques présentes ou veulent développer des nouvelles techniques de ML adapté pour leur domaine d'intérêt.

Chargé de cours: Bowen Peng (Étudiant M.Sc à UdeM sous co-supervision par LIGUM et MILA)
Email: bo.wen.peng@umontreal.ca
Consultation/Questions: préférablement après le cours, ou par email.

Auxiliaires d’enseignement: TBA

Le cours couvrira les sujets suivants: notions générales (terminologie de base, généralisation, malédiction de la dimensionnalité, bias-variance, capacité, comparaison des classifieurs), algorithmes supervisés (k plus proches voisins, classifieurs linéaires, réseaux de neurones MLP, CNN, RNN, méthodes d'ensemble), survol des algorithmes non-supervisés (analyse en composantes principales, méthode de k-moyennes).

Il y aura 7 sessions au total, un cours de 2 heures par semaine. Le cours sera donné en Français, mais les slides seront en Anglais pour faciliter l’apprentissage des termes communs. Chaque cours théorique est accompagné d’un ensemble d’exercices pratiques en Python. Il y aura un survol de ces exercices si le temps permet à la fin de chaque cours.

Prévoyez 2h de cours et 2-6h de travail/lecture personnelle par semaine si vous n’avez aucune expérience en ML. Il y aura aussi occasionnellement des quiz choix multiples sur google forms pour vous donner une idée de votre progrès. Vous aurez une semaine pour faire chaque quiz.

Un concours de kaggle (en équipe de 2 ou plus) servira de projet et de l’évaluation finale. Le concours dure 4 semaines et commence à partir du cours 3. Il y aura une présentation courte à faire à la fin. Vous présenterez vos méthodes et résultats à vos collègues.
La charge de travail au total (incluant les cours) est d’environ 30 à 60 heures, dépendamment de la personne et du travail/lecture additionnel effectué pour le concours.


1. Introduction et terminologie de l'apprentissage.
    - Exercices: Introduction à la librairie Numpy et au traitement numérique parallèle.


2. Tâches de l'apprentissage, méthodes à base d'histogramme et méthodes à base de voisinage.
    - Implémentation des modèles histogramme, k-NN et KDE.
    - Quiz 1, à compléter avant le cours 3.


3. Cadre général de l'apprentissage, évaluation de performance, sélection de modèle, notion de capacité.
    - Implémentation des méthodes de sélection. Introduction à la librairie scikit-learn.
    - Début du concours Kaggle.


4. Régression et classification linéaire. Descente de gradient.
    - Implémentation des modèles linéaires. Évaluation de la performance des algorithmes. Introduction à la librairie Pandas.
    - Quiz 2, à compléter avant le cours 5.


5. Réseaux de neurones de type MLP, backpropagation, deep learning.
    - Implémentation du MLP. Entraînement des réseaux de neurones avec la version implémenté en numpy et avec la version de scikit-learn.


6. Survol des méthodes d'ensemble, réseaux de neurones convolutifs (CNN), récurrentes (RNN) et apprentissage non-supervisé, réduction de dimensionnalité (PCA, etc.), partitionnement (k-moyennes, etc.).
    - Introduction à la librairie Keras.
    - Quiz 3, à compléter avant le cours 7.


7. Résumé de la matière et discussion/présentation des méthodes/résultats du concours Kaggle par les étudiants.
    - Le concours se termine exactement à 23:59 le jour avant le cours 7.