# Machine Learning Projects



## Description

This a collection of introductory machine learning projects intended to be a demonstartion of how to make use some of the most common data sets that are available to a beginner in data science and machine learning.

## 1. Breast Cancer Wisconsin (Diagnostic) Data Set
>This dataset is a binary classification problem. 

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.A patients diagnosis maybe either be 2 for benign or  4 for malignant. We make use of the KNeighbours Classifcation and Logistic Regression models.


## 2. Predicting Survivors From The Titanic Shipwreck

> An application of machine learning classifaction algothrims

On April 15, 1952 the RMS Titanic set sails on her maiden voyage. Knwons the latgest ship at the time, the behemoth was deemed unsinkable. Unfortunately nature would prove otherwise, as the Titanic crashed into an iceberg and sank. More than 1500 people lost their lives making this event one of the deadilest of a single ship.\
This program aims to make use of the information avaiable about the passengers of the Titanic to predict which of the passengers would survive.


## 3. SMS SPAM CLASSIFIER

> Using NLP and machone learning algothrims to classify sms messages as spam

Using the data from UCL ML Datasets this programs aims to predict if a text is spam or not.

We use two tokenization methods: TfidfVectorizer and CountVectorizer from the sklearn module.


### TfidfVectorizer
Converts documents to a matrix of TF-IDF features.

##### Term frequency

$$TF_{word,document} = \frac{number \ of \ times \ word \ appears \ in \ document}{total\ number\ of\ words\ in\ document}$$

#### Inverse document frequency

$$ IDF_{word} = \log\left(\frac{total\ number\ of\ documents}{ number\ of\ documents\ containing\ word}\right) $$

TfidfVectorizer = TF*IDF 

### CountVectorizer
Convert a collection of text to a matrix of token counts.

This program aims to use Logistic Regression and Random Forest models to predict if a given message in the dataset is a spam message or not



## Author info
Bruce Mvubele \
[LinkedIn](https://www.linkedin.com/in/bruce-mvubele-494105143/) \
e-mail: cmvubele@gmail.com
