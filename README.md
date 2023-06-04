# Predicting Violence Against Women

## Table of Contents


## 📝 Description

During my postgraduate studies in the Data and Web Science program at Aristotle University of Thessaloniki, I completed the aforementioned project as part of the Machine Learning course. The project's goal was to analyze the data, process it correctly, and then use it to train machine learning algorithms to anticipate the impact of abusive acts on the victims' subsequent lives. The target variable in the dataset is OUTCOME.

## 📚 Dataset

Violence Against Women dataset from the Pacific Data Hub data source comprises records gathered from several official international surveys reporting on indicators linked to violence against women in 22 Pacific Ocean nations. These data refer to the period 2006 - 2019.

## 🖥️ Installation

### 🛠️ Requirements
* Python >= 3.6
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Imbalanced-learn
* XGBoost

### ⚙️ Setup

All of the above packages can be installed from the following commands.

```bash
pip install numpy
pip install pandas
pip install matplotlib
pip install -U scikit-learn
pip install -U imbalanced-learn
pip install xgboost

```


## ⏳ Data Preprocessing

* Drop of insignificant features
* Seperate features into numerical features and categorical
* Impute missing values of numerical features using KNNImputer
* Impute missing values of categorical features using SimpleImputer
* Encode categorical features using OneHotEncoder
* Scaling features using MinMaxScaler
* PCA is used to reduce dimensionality by adjusting the variance of the input that is expected to be explained by the produced components.
* Over Sampling using RandomOverSampler in order to deal with the imbalance of classes in the dataset.
* Impute missing values of dependent variable OUTCOME: Outcome using Clustering
* K-Fold Cross Validation used to split all the samples in 10 groups of samples
* Saving final dataset with all values filled

## 🎯 Modeling and Evaluation

### Models

* Logistic Regression
* Decision Trees
* Random Forest
* K-Nearest Neighbors
* Naive Bayes
* Multilayer perceptron
* Support Vector Machine

### Evaluation Metrics

* Total Training Time
* Accuracy
* Precision
* Recall
* F1-Score
