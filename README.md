# Glioma Grading with Machine Learning

This project focuses on using machine learning techniques to classify LGG (Lower-Grade Glioma) and GBM (Glioblastoma Multiforme). The dataset used for this project aims to find the optimal subset of mutation genes and clinical features for the glioma grading process, with the objective of improving performance and reducing costs.

## Dataset
The dataset used in this project can be found [here](https://archive.ics.uci.edu/dataset/759/glioma+grading+clinical+and+mutation+features+dataset).

Citation:
Tasci, Erdal; Camphausen, Kevin; Krauze, Andra Valentina; and Zhuge, Ying. (2022). Glioma Grading Clinical and Mutation Features. UCI Machine Learning Repository. [DOI:10.24432/C5R62J](https://doi.org/10.24432/C5R62J).

## Models Compared
Several machine learning models were compared to classify the targets. These include:

- LinearSVC
- RandomForestClassifier
- GradientBoostingClassifier
- LogisticRegression
- SGDClassifier
- Perceptron
- NearestCentroid
- GaussianProcessClassifier
- XGBClassifier

Additionally, LazyClassifier was employed to aid in the selection of the best-performing model.

## Tools and Libraries Used
- Python 3.11.7
- Jupyter
- pandas 1.2.4
- numpy 1.26.4
- scikit-learn 1.2.2
- xgboost 2.0.3
- lazypredict 0.2.12
- matplotlib 3.8.0


## Model Performance - Confusion Matrix

![Confusion Matrix](https://github.com/mohammadhosseinparsaei/Glioma-Grading/blob/main/output.png)
