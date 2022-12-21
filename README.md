# DMML2022_Apple

# Detecting the difficulty level of French texts


# About the project 


During our Master class, Data mining and machine learning, we have joined a competition on [Kaggle.](https://Kaggle.com)com. The goal was to build a model for English speakers that predicts the difficulty of a French written text between A1 to C2.

### Description of the project 


First of all, we have identified a problem that many language learners face: it is often difficult to find texts that are at an appropriate level of difficulty for their current language skills. With this in mind, we have developed a model that predicts the difficulty of French texts, with the goal of helping language learners find texts that are at an appropriate level of difficulty for their skill level.

The data that we used to build our model includes : labeled training data and unlabelled test data. The variety techniques that we used include : logistic regression, kNN, decision trees, and random forests, to build and train our model. In order to find better solution, we have also performed hyper-parameter optimisation like grid Search. In evaluating our model, we have considered various metrics, including precision, recall, F1-score, and accuracy.

We are excited to share our solution with you and hope that it will be useful for language learners looking for texts at the right level of difficulty. We invite you to try out our model and see how it performs. 

## Build with 


To construct this model, we used three dataset that we found on kaggle.com.


- **training_data.csv** - the training set
- **unlabelled_test_data.csv** - the test set
- **sample_submission.csv** - a sample submission file in the correct format

The columns that we found in those dataset are : 


- `id`: Numerical identifier of the sentence.
- `sentence`: A sentence in French for which you want to predict the difficulty level.
- `difficulty`: The difficulty level of the sentence (from A1 to C2). This column would be your target variable.

