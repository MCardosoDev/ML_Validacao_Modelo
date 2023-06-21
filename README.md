# ML Validação de modelos

* Curso Alura: Machine Learning: Validação de modelos

- Variável Dummie
- Árvore de decisão
- Validação cruzada
- KFold
- GroupKFold
- StandardScaler
- SVC
- Acurácia
- Aleatoriedade de modelo
- Pipeline

    - import pandas as pd
    - import numpy as np
    - from sklearn.model_selection import train_test_split
    - from sklearn.svm import LinearSVC
    - from sklearn.metrics import accuracy_score
    - from sklearn.dummy import DummyClassifier
    - from sklearn.tree import DecisionTreeClassifier
    - from sklearn.model_selection import cross_validate
    - from sklearn.model_selection import KFold
    - from sklearn.model_selection import StratifiedKFold
    - from sklearn.model_selection import GroupKFold
    - from sklearn.preprocessing import StandardScaler
    - from sklearn.svm import SVC
    - from sklearn.pipeline import Pipeline