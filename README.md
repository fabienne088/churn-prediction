# Customer Churn Analysis 💳

[![forthebadge made-with-python](https://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

## 🧐 Description
An important financial institution is interested in analyzing its client database to increase the revenue generated from credit cardholders. They are concerned about customers closing their bank accounts after accepting products from other institutions.

The churn rate is above 15% and increasing, the CEO urges the marketing team to start a marketing campaign for client retention.

The mission:

- Predict those clients with more propensity to close their bank account with the financial institution
- Find possible groups of clients and define their characteristics. This will help the marketing team to design custom-made campaigns to increase customer retention. (will be discussed later)

![customer churn](src/0_g8Tw7FNqfLJXptYE.webp)

What is Churn Rate?

_The churn rate, also known as the rate of attrition or customer churn, is the rate at which customers stop doing business with an entity. It is most commonly expressed as the percentage of service subscribers who discontinue their subscriptions within a given time period._

[More info](https://www.investopedia.com/terms/c/churnrate.asp)

## 📦 Repo structure

```md

├── data\
│   ├── BankChurners.csv
│   ├── churners_clean_df.csv
│   └── churners_df.csv
│
├── src\
│   └── 0_g8Tw7FNqfLJXptYE.webp
│
├── visuals\
│   ├── decision_tree_grphviz
│   ├── decision_tree_grphviz.png
│   ├── decistion_tree.log
│   ├── decistion_tree.png
│   ├── feature_importance.png
│   ├── heatmap.png
│   ├── pairplot.png
│   ├── roc.png
│   └── smotenc.png
│
├── .gitignore
├── README.md
├── classification.ipynb
├── exploration.ipynb
└── requirements.txt

```

## ⏏️ Getting Started

### 📚 Prerequisities

To run the project, you need to install the required libraries. You will find them in the ```requirements.txt``` file.

You can click on the badge links to learn more about each library and its specific version used in this project. You can install them manually using pip install <library name> or just running pip install -r requirements.txt.

   - [![python version](https://img.shields.io/badge/python-3.x-blue)](https://python.org)
   - [![Pandas version](https://img.shields.io/badge/pandas-2.x-green)](https://pandas.pydata.org/)
   - [![NumPy version](https://img.shields.io/badge/numpy-1.x-orange)](https://numpy.org/)
   - [![matplotlib version](https://img.shields.io/badge/matplotlib-3.x-red)](https://matplotlib.org/)
   - [![Seaborn version](https://img.shields.io/badge/seaborn-0.x-yellow)](https://seaborn.pydata.org/)
   - [![sklearn version](https://img.shields.io/badge/scikit_learn-1.x-%f89938?color=%f89938)](https://scikit-learn.org/stable/)
   - [![imblearn version](https://img.shields.io/badge/imblearn-0.x-%f89938?color=%f89938)](https://imbalanced-learn.org/stable/)
   - [![scipy version](https://img.shields.io/badge/scipy-1.x-%f89938?color=%f89938)](https://scipy.org/)
   - [![graphviz version](https://img.shields.io/badge/graphviz-2.x-%f89938?color=%f89938)](https://graphviz.org/)
 

### ⚙️ Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/fabienne088/churn-prediction.git
    ```

2. Navigate to the project directory:
    ```bash
    cd churn-prediction
    ```

3. You're all set! You can now go through the `exploration`and  `classification` notebooks. <br>
Enjoy!

## 📋 Usage
To use this repository, follow these steps:

1. **Clone the Repository**: 
    - Clone the repository to your local machine using the following command:
    ```bash
    git clone https://github.com/fabienne088/churn-prediction.git
    ```

2. **Navigate to the Project Directory**:
    - Once cloned, navigate to the project directory:
    ```bash
    cd churn-prediction
    ```

3. **Go trough the notebooks**:
    - In the `exploration` file you can find the  Exploratory Data Analysis (EDA).
    
    - And in the `classification` file you can find the resampling of the Imbalaced Data, preprocesing steps, classification models and evaluation.

4. **Look into visuals**:
    - The `visuals` directory contains visualizations, including a decision tree.

## 💡Data Sources

Kaggle: 
- [Credit Card customers dataset](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)
- [Credit Card Customer Segmentation + EDA](https://www.kaggle.com/code/tkunzler/credit-card-customer-segmentation-eda#TABLE-OF-CONTENTS) 
- [Customer Attrition Prediction](https://www.kaggle.com/code/messier74/customer-attrition-prediction)
- [Bank churn prediction](https://www.kaggle.com/code/jeffaj/bank-churn-prediction-recall-96-87-acc-95-68/notebook#2.-EDA-:-Exploratory-data-analysis)
- [Credit Card Customers Churn Prediction](https://www.kaggle.com/code/abraamsaid/credit-card-customers-churn-prediction#1--Import-Libraries-%F0%9F%93%9A)

Analytics Vidhya:
- [Guide to AUC ROC Curve in Machine Learning : What Is Specificity?](https://www.analyticsvidhya.com/blog/2020/06/auc-roc-curve-machine-learning/)
- [10 Techniques to Solve Imbalanced Classes in Machine Learning (Updated 2024)](https://www.analyticsvidhya.com/blog/2020/07/10-techniques-to-deal-with-class-imbalance-in-machine-learning/)

GitHub: 
- [How to handle imbalanced datasets](https://github.com/dataprofessor/imbalanced-data/blob/main/imbalanced_learn.ipynb)

DataCamp:
- [Decision Tree Classification in Python Tutorial](https://www.datacamp.com/tutorial/decision-tree-classification-python)

Imbalanced-learn:
- [imbalanced-learn documentation](https://imbalanced-learn.org/stable/index.html)
- [SMOTENC](https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.SMOTENC.html)

Scikit-learn:
- [KNeighborsClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
- [RamdomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
- [DecisionTreeClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)

## 🎨 Visuals
**Correlation Heatmap of numerical categories :**

<img src="visuals\heatmap.png" width="800" height="600">

<br>

**Resampling with SMOTENC :**

<img src="visuals\smotenc.png" width="300" height="300">

<br>

**Evaluation of the models with ROC curve:**

<img src="visuals\ROC.png" width="500" height="400">


## ⏱️ Timeline
This project took form in five days.

## 📌 Personal Situation
This project was made as part of the AI Bootcamp at BeCode.

## 🔧 Maintainers
Connect with me on [LinkedIn](https://www.linkedin.com/in/fabienne-th%C3%BCer-56a8a0a?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BGVOLSNIkQnaKEDrsWD%2BY6w%3D%3D).
