# Data Visualization Course Final Project
> by Kfir Goldfarb

<a href="https://github.com/kggold4">
<img src="images/b-01.png" width="25px" height="25px" align="left"></a>
<a href="https://www.linkedin.com/in/kfir-goldfarb/">
<img src="images/b-02.png"  width="25px" height="25px" align="left"></a>
<a href="mailto:kfir.goldfarb@msmail.ariel.ac.il">
<img src="images/b-03.png" width="25px" height="25px" align="left"></a>
<a href="https://www.youtube.com/channel/UCypEWlruyG_I5A48GqB5c6g">
<img src="images/b-04.png" width="25px" height="25px" align="left"></a>
<a href="https://www.hackerrank.com/kggold4?hr_r=1">
<img src="images/b-05.png" width="25px" height="25px" align="left"></a>
<a href="https://stackoverflow.com/users/14749277/kfir-goldfarb">
<img src="images/b-06.png" width="25px" height="25px" align="left"></a>

<br>

## <i>Final project in the data visualization cource at Ariel University</i>

In this project we have a lot of data that we want to perform classification problems on it using data visualization, dimensionality reduction, ensemble learning and unsupervised learning.

### This project contains 4 parts and each part have a single notebook:
1. Part 1 - [task_1](task_1.ipynb) notebook, Improving My Introduction to Data Science Course Final Project Classification Problem(<a href="https://github.com/kggold4/final-project-intro-data-science/blob/main/notebook3.ipynb">Notebook 3</a>) using ensemble and usupervised learning.
1. Part 2 - [task_2](task_2.ipynb) notebook, Dimensionality Reduction, PCA and Classification using ensemble and usupervised learning for <b>Fashion MNIST</b> Dataset.
1. Part 3 - [task_3](task_3.ipynb) notebook, Dimensionality Reduction, PCA and Classification using ensemble and usupervised learning for <b>Cat & Dog</b> dataset.
1. Part 4 - [task_4](task_4.ipynb) notebook, Classification using ensemble and usupervised learning on the <b>Hands</b> datasets.

# <u>For Lecturer (Roi) - Please read [README.pdf](README.pdf) file</u>

## <i> Classificaion Results: </i>

### Notebook 1:

| Model | Accuracy |
| ------ | ------ |
| KNN | 70.40 % |
| DecisionTree | 72.40 % |
| LogisticRegression | 77.60 % |
| Hard Voting | 74.80 % |
| Soft Voting | 76.80 % |
| Bagging | 77.60 % |
| Pasting | 77.20 % |
| Random Forest | 74.40 % |
| AdaBoost | 77.60 % |
| Gradient Boost | 78.80 % |
| XGradient Boost | 76.40 % |

### Best Model - Gradient Boost - 78.80 %

<hr>

### Notebook 2:

 - 154 PCA Components:

| Model | Accuracy |
| ------ | ------ |
| KMeans | 7.29 % |
| Bagging | 74.38 % |
| Pasting | 74.88 % |
| Random Forest | 84.83 % |
| AdaBoost | 84.81 % |
| XGradient Boost | 88.14 % |
| Grid Search with Random Forest | 86.28 % |
| Grid Search with XGradient Boost | 86.81 % |

### Best Model - Extreme Gradient Boostring Classifier - 88.14 %

 - 50 PCA Components:

| Model | Accuracy |
| ------ | ------ |
| KMeans | 1.47 % |
| Bagging | 76.08 % |
| Pasting | 76.20 % |
| Random Forest | 85.56 % |
| AdaBoost | 86.17 % |
| XGradient Boost | 87.53 % |
| Grid Search with Random Forest | 86.45 % |
| Grid Search with XGradient Boost | 87.11 % |

### Best Model - Extreme Gradient Boostring Classifier - 87.53 %

 - 24 PCA Components:

| Model | Accuracy |
| ------ | ------ |
| KMeans | 16.30 % |
| Bagging | 76.06 % |
| Pasting | 76.05 % |
| Random Forest | 85.13 % |
| AdaBoost | 85.94 % |
| XGradient Boost | 86.36 % |
| Grid Search with Random Forest | 85.68 % |

### Best Model - Extreme Gradient Boostring Classifier - 86.36 %


<hr>

### Notebook 3:

 - 335 PCA Components (100^2 pixels images greyscale):

| Model | Accuracy |
| ------ | ------ |
| Bagging Classifier | 55.28 % |
| Pasting Classifier | 54.52 % |
| Random Forest Classifier | 60.80 % |
| AdaBoostring Classifier | 56.20 % |
| Extreme Gradient Boostring Classifier(Binary) | 64.36 % |
| Grid Search with Random Forest Classifier | 61.75 % |
| Grid Seach with Extreme Gradient Boostring Classifier(Multi) | 64.04 % |

### Best Model - Extreme Gradient Boostring Classifier - 64.36 %

 - 300 PCA Components (30^2 pixels images no greyscale):

| Model | Accuracy |
| ------ | ------ |
| Bagging Classifier | 57.12 % |
| Pasting Classifier | 56.64 % |
| Random Forest Classifier | 63.62 % |
| AdaBoostring Classifier | 56.46 % |
| Extreme Gradient Boostring Classifier(Binary) | 65.84 % |
| Grid Search with Random Forest Classifier | 63.00 % |
| Grid Seach with Extreme Gradient Boostring Classifier(Multi) | 66.20 % |

### Best Model - Grid Seach with Extreme Gradient Boostring Classifier - 66.20 %

 - 185 PCA Components (30^2 pixels images no greyscale):

| Model | Accuracy |
| ------ | ------ |
| Bagging Classifier | 58.32 % |
| Pasting Classifier | 57.00 % |
| Random Forest Classifier | 64.48 % |
| AdaBoostring Classifier | 57.50 % |
| Extreme Gradient Boostring Classifier(Binary) | 65.40 % |
| Grid Search with Random Forest Classifier | 63.61 % |
| Grid Seach with Extreme Gradient Boostring Classifier(Multi) | 65.98 % |

### Best Model - Grid Seach with Extreme Gradient Boostring Classifier - 65.98 %

<hr>

### Notebook 4:

| Model | Accuracy |
| ------ | ------ |
| KNN | 88.69 % |
| DecisionTree | 62.76 % |
| LogisticRegression | 82.86 % |
| Bagging | 81.06 % |
| Pasting | 82.41 % |
| Random Forest | 81.78 % |
| AdaBoost | 78.73 % |
| Stacking | 82.49 % |
| XGradient Boost | 70.85 % |
| Grid Search with Random Forest | 86.49 % |
| Grid Seach with XGradient Boost | 83.95 % |

### Best Model - KNN - 88.69 %
