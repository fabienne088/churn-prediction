# Customer Churn Analysis 💳

[![forthebadge made-with-python](https://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

## 🧐 Description
An important financial institution is interested in analyzing its client database to increase the revenue generated from credit cardholders. They are concern about customers closing their bank accounts after accepting products from other institutions.

The churn rate is above 15% and increasing, the CEO urges the marketing team to start a marketing campaign for client retention.

Your mission:

- Predict those clients with more propensity to close their bank account with the financial institution
- Find possible groups of clients and define their characteristics. This will help the marketing team to design custom-made campaigns to increase customer retention.

![alt text](src/0_g8Tw7FNqfLJXptYE.webp)

#### What is Churn Rate ?

_The churn rate, also known as the rate of attrition or customer churn, is the rate at which customers stop doing business with an entity. It is most commonly expressed as the percentage of service subscribers who discontinue their subscriptions within a given time period._

[More info](https://www.investopedia.com/terms/c/churnrate.asp)

## 📦 Repo structure

```md


├── src\
│   └── 0_g8Tw7FNqfLJXptYE.webp
│
├── .gitignore
├── 08-customer_churn_analysis.md
├── BankChurners.csv
├── README.md
├── ROC.ipynb
├── ROC.png
├── churners_clean_df.csv
├── churners_df.csv
├── decision_tree_grphviz
├── decision_tree_grphviz.png
├── decistion_tree.log
├── decistion_tree.png
├── exploration.ipynb
├── imbalanced_data.ipynb
├── outliers.ipynb
├── preperation.ipynb
└── trees.ipynb

```

## 🏁 Getting Started

### 📚 Prerequisities

To run the project, you need to install the required libraries. 

You can click on the badge links to learn more about each library and its specific version used in this project. You can install them manually using pip install <library name> or just running pip install -r requirements.txt.

Install the required libraries:

   - [![python version](https://img.shields.io/badge/python-3.x-blue)](https://python.org)
   - [![Pandas version](https://img.shields.io/badge/pandas-2.x-green)](https://pandas.pydata.org/)
   - [![NumPy version](https://img.shields.io/badge/numpy-1.x-orange)](https://numpy.org/)
   - [![matplotlib version](https://img.shields.io/badge/matplotlib-3.x-red)](https://matplotlib.org/)
   - [![Seaborn version](https://img.shields.io/badge/seaborn-0.x-yellow)](https://seaborn.pydata.org/)
   - [![sklearn version](https://img.shields.io/badge/scikit_learn-1.x-%f89938?color=%f89938)](https://scikit-learn.org/stable/)
   - [![imblearn version](https://img.shields.io/badge/imblearn-0.x-%f89938?color=%f89938)](https://imbalanced-learn.org/stable/)
   - [![scipy version](https://img.shields.io/badge/scipy-1.x-%f89938?color=%f89938)](https://scipy.org/)
   - [![graphviz version](https://img.shields.io/badge/graphviz-2.x-%f89938?color=%f89938)](https://graphviz.org/)

Install the packages from the ```requirements.py``` file.
   

### ⚙️ Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/fabienne088/churn-prediction.git
    ```

2. Navigate to the project directory:
    ```bash
    cd churn-prediction
    ```

3. You're all set! You can now explore the `data` and `model` directories. You can find the script for the app in `app.py`.<br>
Enjoy!

## 🎈 Usage
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

3. **Explore the data**:
    - The `data` directory contains the dataset used. Explore the data file to understand its structure and contents. You can use the included Jupyter Notebook for it.

4. **Access the model**:
    - The `model` directory contains a train.py that trains the RandomForestRegression model and evaluate it, and a predict.py that predicts the price of a house based on a given dataset.

5. **Explore the script app.py**
    - The `app.py` script contains everything for running the app.

6. **Open the app** 🎉

    [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://immo-eliza-deployment-3pzskfv3wyawvpj4u52pwg.streamlit.app/)

## 🎨 Visuals
Will be added soon.

## 👑 Resources
[Streamlit documentation](https://docs.streamlit.io/)

[Deploy your app](https://docs.streamlit.io/streamlit-community-cloud/deploy-your-app)


## ⏱️ Timeline
This project took form in five days.

## 📌 Personal Situation
This project was made as part of the AI Bootcamp at BeCode.org.

## 🔧 Maintainers
Connect with me on [LinkedIn](https://www.linkedin.com/in/fabienne-th%C3%BCer-56a8a0a?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BGVOLSNIkQnaKEDrsWD%2BY6w%3D%3D).
