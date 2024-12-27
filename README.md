## kaggle-titanic-solution-machine-learning 
kaggle titanic solution with machine learning

This repository presents my submission in the https://www.kaggle.com/competitions/titanic .

The goal of the project is to create a machine learning model that predicts whether a passenger survived the Titanic shipwreck or not.
We have access to a bunch of 9 features (numerical, text, categorical). The big challenge with this competition is the size of the data we have. The training set is composed of only 891 samples. The testing set is composed of 418 samples.
Therefore, the main issue is to design an algorithm which generalizes enough in order to avoid over-fitting. To do so, a bunch of features is generated. Then, an ensemble modeling method with voting is used in order to get the most generalized model.

## Data

The repository provides two datasets: a training set (train.csv) and a test set (test.csv).

Variable Notes
pclass: A proxy for socio-economic status (SES) 1st = Upper 2nd = Middle 3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way... Sibling = brother, sister, stepbrother, stepsister Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...

Parent = mother, father Child = daughter, son, stepdaughter, stepson Some children travelled only with a nanny, therefore parch=0 for them.

Embarked: Port of Embarkation C = Cherbourg, Q = Queenstown, S = Southampton

Survival: 0 = No, 1 = Yes



## Built With

Python - Programming language

Jupyter Notebook - Web application for creating and sharing documents that contain live code, equations, visualizations and narrative text

Pandas - Data analysis and manipulation tool

NumPy - Library for working with arrays

Matplotlib - Library for creating static, animated, and interactive visualizations

Seaborn - Data visualization library based on matplotlib

Scikit-learn - Machine learning library for the Python programming language


## What do we do in this repository?

first We  use feature engineering to help the model. 

Next, we prepare the data for the machine learning model. 

In th Next step, we test different machine learning models to see which ones perform best and we optimize them with GridSearch. Finally, we use PCA, MDS, TSNA, and feature importance to find out which features help us the most.

