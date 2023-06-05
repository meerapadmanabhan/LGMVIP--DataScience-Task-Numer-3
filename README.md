# LGMVIP--DataScience-Task-Numer-3
BEGINNER LEVEL TASK: Music Recommendation System

Music recommender systems can suggest songs to users based on their listening patterns.

# LGMVIP--DataScience-Task-Numer-3

## Table of Content

1. Introduction
2. Classification Models

   Logistic Regression

   Random Forest
 
   KNN
 
   Decision Tree
   
   LightGBM 
 
7. Results
8. Conclusion

## INTRODUCTION

The Music Recommendation system is all about recommending the songs which the user like based on their previous activities like searches, previously listened songs, etc. There are many techniques for building a recommendation like Collaborative Filtering, Content Based filtering, Hybrid methods (Combining both Content Based and Collaborative Filtering methods).

In this challenge we have to build a recommendation system that can predict whether a user will listen to a song again within one month after the user's very first observable listening event in KKBox application. If the user did not listen to the song again within one month, the target variable will be 0, and 1 otherwise. 

## CLASSIFICATION MODELS

Classification models can be used to predict the dependent variable. Here we are going to use 5 different algorithms for classification namely, K-Nearest Neighbours, Decision Tree, LightGBM, Random Forest and Logistic Regression. Atlast we compare their accuracy to find the suitable classification technique for this problem. The given dataset is seperated into two seperate train and test sets. The train set is used to train the model, and the test set is used to predict the accuracy of each model. Finally, we compare the results. Here, 70% of the dataset was considered for training and 30% of the dataset for testing.

### Accuracy of Each Model using test data

|     Algorithm           | Accuracy  |
|------------------------:|-----------|
|   K Nearest Neighbour   |     72    |
|   Decision Tree         |     73    |
|   Random Forest         |     79    |
|   Logistic Regression   |     74    |
|   LightGBM              |     78    |

## RESULT
This brings us to a conclusion that RandomForest and LGM perform very well in test data. But RandomForest in some cases tend to overfit the data. So LigthGBM is better at predicting the music the user needs. It provides the users 78.5% accuracy on global data, basically it generalizes very well.

## CONCLUSION
The purpose of this project was to compare different classification algorithms to predict music recommender systems can suggest songs to users based on their listening patterns.. Find and compare the accuracy of each model to find the best classifier. Finally train the model using the complete dataset.

The final_model computed here can be used to predict music recommender systems can suggest songs to users based on their listening patterns.
--
#### MEERA P V
