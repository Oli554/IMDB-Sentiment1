# IMDB-Sentiment1
This project focuses on binary sentiment classification in which we are trying to determin whther a given reiew is positive or negative.
The goal of the project is to also compare models and evaluates their performances sing accuracy, precision recall conduson matrix and F1 score.
Workflow:
1. importing Libraries:
we start by importing Libraries that are important for data manipulation text preprocesssing machine learnign visualisaion and deep learning 
2. Loading Dataset:
the CSV file is loaded into the Data frame while converting the sentiment labels into numerical ones in which positive == 1 and negative == 0
3. EDA
we perform basic analysis to understand the dataset structure such as checking the shape and type of teh data as well as missing values and duplicated rows
4. Text preprocessing:
we clean the review text before extracting and deep learning training steps that can include decoding HTML entitites, coverting text yo lower case, removing extra spaces, keeping only useful content
5. Vader and TextBlob:
for the baseline model sentence-level polarity features are extracted. Features that convert each review into a small numerical vector representing sentiment intensity 
6. Train/ validation /  test Split:
we split the data set into 60% training 20% validation and 20% test
7. Feature Scaling:
the scaler used fit only on the training data and we applied it to the training validation and test sets to ensures proper normalisation 
8. MLP classifier:
a baseline model used to train lexion based features. 
9. LSTM model:
a RNN model chosen so help processing sequential data and because it is better at learning word order and  contextual meaning 
During this step we used tokenization to clean the text, and  we converted the text to integer sequece 
10. CNN model:
we used this third model for text classification as this model can learn local patterns such as important phrases and short sentiment expressions
11. Evaluation and comaparison:
the metrics used to evaluate the modelswere accuracy precisio recall F1 score and the confusion matrix in which at the end of the notebook the models are compared in the result table
