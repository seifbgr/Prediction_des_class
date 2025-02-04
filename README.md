# Prédiction de Classe

## Description
Ce projet vise à prédire une classe cible en utilisant des techniques d'apprentissage automatique. Il comprend le prétraitement des données, la sélection des variables, ainsi que des méthodes d'équilibrage des classes.

## Contenu du projet
- **Classe_prediction.ipynb** : Notebook Jupyter contenant l'analyse et l'entraînement du modèle.
- **Données** : Les données utilisées pour l'entraînement et le test du modèle.
- **README.md** : Ce fichier expliquant le projet.

## Prérequis
Avant d'exécuter le notebook, assurez-vous d'avoir les bibliothèques suivantes installées :

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Exécution
1. Clonez le dépôt :

```bash
git clone https://github.com/votre-utilisateur/nom-du-repo.git
cd nom-du-repo
```

2. Ouvrez le notebook et exécutez les cellules dans l'ordre.

## Principales méthodes utilisées
- **Encodage des variables qualitatives**
- **Sélection des variables importantes**
- **Sur-échantillonnage pour équilibrer les classes**
- **Prédiction et évaluation du modèle**

## Algorithmes utilisés
Les algorithmes testés dans ce projet sont :
- **Régression Logistique**
- **Random Forest**
- **Gradient Boosting**
- **KNN**
- **AdaBoost**
- **Bagging Classifier**

Les meilleurs algorithmes en termes de performance sont **Random Forest** et **Gradient Boosting**, offrant une bonne précision et un bon équilibre des classes.

## Résumé du Travail Réalisé
### Prétraitement des Données
- Sélection des variables les plus pertinentes pour l'analyse.
- Encodage des variables catégorielles afin de les rendre exploitables par les algorithmes de Machine Learning.
- Gestion du déséquilibre des classes cibles : mise en place de techniques comme le suréchantillonnage ou le sous-échantillonnage pour équilibrer les classes avant l'entraînement des modèles.

### Partition des Données
Séparation du jeu de données en trois ensembles :
- **Entraînement (60%)** : utilisé pour ajuster les modèles.
- **Validation (20%)** : utilisé pour optimiser les hyperparamètres et comparer les modèles.
- **Test (20%)** : utilisé pour évaluer la performance finale du meilleur modèle.

### Modélisation & Optimisation
- Expérimentation avec six algorithmes de classification.
- Optimisation des hyperparamètres via une recherche par validation croisée (5-fold Cross Validation).

### Évaluation & Sélection du Modèle
- Comparaison des performances des modèles sur l’ensemble de validation.
- Classement des modèles en fonction de plusieurs métriques (Accuracy, Précision, Recall, F1-score).

### Validation Finale
- Test du meilleur modèle sur l’ensemble de test afin d’obtenir une évaluation objective et généralisable.

## Conclusion
L’approche adoptée garantit une sélection rigoureuse du modèle optimal, en évitant le surapprentissage et en assurant une bonne généralisation sur de nouvelles données, tout en prenant en compte le déséquilibre des classes cibles pour améliorer les performances des modèles sur des jeux de données déséquilibrés. 🚀

## Auteur
- Seif Bgra


