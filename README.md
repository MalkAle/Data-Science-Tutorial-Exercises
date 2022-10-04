# Overview

In this repository I put 2 of the many coding exercises from the Data Science tutorial that I have completed recently (Udemy, "Python for Data Science and Machine Learning Bootcamp" by Jose Portilla, https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/). The exercises small projects that I have coded myself prior to completing several code along lectures on the same topic. The projects are created using Jupyter Notebook and Python libraries NumPy, Pandas, Matplotlib, Seaborn, Scikit learn and Keras/Tensorflow). The 2 projects from this repository are described more in detail below.

# Advertizing Logistic Regression

The first exercise a fake advertising data set from Kaggle (https://www.kaggle.com/datasets/bumba5341/advertisingcsv?resource=download&select=Advertising.csv) indicating whether or not a particular internet user clicked on an Advertisement. The goal is to create a model that will predict whether or not they will click on an ad based off the features of that user. The project consists of the following steps.

- Import data from a csv file
- Check for missing data
- Explore features using data engineering and visualization (seaborn histplot, jointplot, pairplot)
- Select and engineer features for use in the machine learning model
- Create regression model with scikit learn using train data with train_test_split and LogisticRegression
- Create predictions using test data
- Evaluate model using classification report

# Lending Club Keras API

The second exercise is more advanced project using a real dataset from Kaggle (https://www.kaggle.com/wordsforthewise/lending-club). The goal of the project is to build a model that can predict wether or nor a borrower will pay back their loan given historical data on loans. The project consists of the following steps.

- Import data from a csv file
- Explore data
- Data preprocessing
  - Check for missing data
  - Filling missing data where it makes sense
  - Select data that is useful for model creation for machine learning
  - Feature engineering
  - Create dummy variables for non-numeric variables
- Machine learning
  - Train-test-split
  - Normalizing data with MinMaxScaler
  - Create a sequential model for the neural network
  - Train model
  - Exporting model as h5 file
  - Evaluating model performance using scikit learn confusion matrix and classification report
