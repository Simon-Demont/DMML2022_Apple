# DMML2022_Apple

# Detecting the difficulty level of French texts


# 🚀About the project 


During our Master class, Data mining and machine learning, we have joined a competition on [Kaggle.](https://Kaggle.com)com. The goal was to build a model for English speakers that predicts the difficulty of a French written text between A1 to C2.

### Description of the project 


First of all, we have identified a problem that many language learners face: it is often difficult to find texts that are at an appropriate level of difficulty for their current language skills. With this in mind, we have developed a model that predicts the difficulty of French texts, with the goal of helping language learners find texts that are at an appropriate level of difficulty for their skill level.

The data that we used to build our model includes : labeled training data and unlabelled test data. The variety techniques that we used include : logistic regression, kNN, decision trees, and random forests, to build and train our model. In order to find better solution, we have also performed hyper-parameter optimisation like grid Search. In evaluating our model, we have considered various metrics, including precision, recall, F1-score, and accuracy.

We are excited to share our solution with you and hope that it will be useful for language learners looking for texts at the right level of difficulty. We invite you to try out our model and see how it performs. 

## 🏗️Build with 


To construct this model, we used three dataset that we found on kaggle.com.


- **training_data.csv** - the training set with 4800 uniques values 
- **unlabelled_test_data.csv** - the test set with 1200 unique values
- **sample_submission.csv** - a sample submission file in the correct format

The columns that we found in those dataset are : 


- `id`: Numerical identifier of the sentence.
- `sentence`: A sentence in French for which you want to predict the difficulty level.
- `difficulty`: The difficulty level of the sentence (from A1 to C2). This column would be your target variable.

We also used several libraries to build model. 


- ScikitLearn :
	- Models : `LogisticRegression`, `LogisticRegressionCV`, `KNeighborsClassifier CountVectorizer`, `TfidfVectorizer`, `GridSearchCV`, `StandardScaler`,  `Pipeline` , `RandomizedSearchCV`, `DecisionTreeClassifier`, `RandomForestClassifier`, `OneVsRestClassifier`, `MultinomialNB`, `LinearSVC`
	- Metrics : `confusion_matrix`, `accuracy_score,` `precision_score`, `recall_score`, `f1_score`, `classification_report`
	- Model selection : `train_test_split`
	- Dummy : `DummyClassifier`
- Pandas
- Numpy
- SciPY :
	- `displacy`
	- `STOP_WORDS`
- Visualisation : 
	- `seaborn`
	- `matplotlib.pyplot`

## How the model works 


📺 [link to our demo on youtube ](https://www.youtube.com/watch?v=kx7P_ENnDPE&list=RDkx7P_ENnDPE&start_radio=1)

## Little feedback 


To conclude this project, we would like to return to some key points. First, it was very interesting to build a model from scratch, having to think about which tools to use and which method to use was very instructive for this course. The organisation of the code was also very instructive, for example, creating functions to avoid redundancy, or using explicit function names, to make the code easier to understand for ourselves and for others who might read it.

Secondly, we would like to come back to some difficulties we encountered. Indeed, the difficulty predictions of a text on which the training set was created surely had its own biases. It was therefore difficult to reproduce a model of our own that could fit exactly the requirements of the basic model. Moreover, the training set had little data to train a powerful machine learning model. As it is often said when talking about machine learning, the more training data there is, the better the machine learning model will be.

## Contributors 

- Yonah Bôle
- Simon Demont
