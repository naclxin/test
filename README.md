# Music Genre Prediction from Audio, Metadata, and Lyric Features

This program is a .ipynb file and can be opened in the jupyter.

In this program, the main tasks can be divided into 4 parts. 

### The first part is for data pre-processing

preprocess() function collects data from data sets and do the pre-pocess.

text_process() function is for Text-processing using TF-IDF, in this function, 
two text type attribute 'title' and 'tags' are processed. 

mergedata() function merges the processed text data into the original dataset.

finaldata() function standarlizes the data and output the final processed data.

### The second part is for data pre-processing

MNB() function builds a Multinomial Naive Bayes based trainning modle 

KNN() function finds the optimal k value and builds a K-Nearest Neighbors based trainning modle 

DT() function builds a Decision Tree based trainning modle

### The third part is for prediction 

predict() function uses trained model to predict a class for the validation data

### The fourth part is for evaluation 

evaluate() function evaluates model performance by accuracy
