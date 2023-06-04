# Predicting Violence Against Women

![ANDREW](https://github.com/dkavargy/violence-against-women/assets/73905168/7a127ae1-2184-4460-a103-bee0bb3defdf)


## 📝 Description

I conducted the mentioned project during my postgraduate studies in the Data and Web Science program at Aristotle University of Thessaloniki, as a part of the Machine Learning course. The primary objective of the project was to analyze and preprocess the data accurately. Subsequently, I utilized machine learning algorithms to predict the potential consequences of abusive acts on the victims' future lives. The target variable in the dataset, referred to as "OUTCOME," was the focal point of the prediction task.

## 📚 Dataset

The dataset on violence against women, obtained from the Pacific Data Hub, includes data collected from various authoritative international surveys conducted in 22 nations located in the Pacific Ocean region. The dataset covers a time span ranging from 2006 to 2019 and contains indicators related to violence against women.

## 🖥️ Installation

### 🛠️ Requirements
* Python >= 3.6
* NumPy
* Pandas
* Seaborn
* Matplotlib
* Scikit-learn


### ⚙️ Setup

All of the above packages can be installed from the following commands.

```bash
pip install numpy
pip install pandas
pip install seaborn
pip install matplotlib
pip install -U scikit-learn
```


## ⏳ Data Preprocessing

* Transform the categorical data to numerical with the use
  of a defined function. The ’_T: Any’ values are transformed to number 0.
* Shows a more Interactive Chart about the distribution of each Topic
* Correlation between the different attributes of dataset
* Face a MultiClass problem and we use all the different labels of the
  OUTCOME column in order to build a classifier model.
* We split the original dataset in 2 parts
* Pass the values in the OneHotEncoder in order to transform them to
  numerical.
* Feature importance we use the Random Forest model.
* For the multiclassification problem we implement 4 different classifiers
* Impute missing values of dependent variable OUTCOME: Outcome using Clustering

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
