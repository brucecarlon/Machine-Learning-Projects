# Machine Learning Projects



## Description

This a collection of inductory machine learning projects intended to be a demonstartion of how to make use some of the most common data sets are available to a beginner in data science and machine learning.

## Breast Cancer Wisconsin (Diagnostic) Data Set
>This dataset is a binary classification problem. 

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.A patients diagnosis maybe either be 2 for benign or  4 for malignant. We make use of the KNeighbours Classifcation and Logistic Regression models.

## SMS SPAM CLASSIFIER

> Using NLP and machone learning algothrims to classify sms messages as spam

Using the data from UCL ML Datasets this programs aims to predict if a text is spam or not.

We use two tokenization methods: TfidfVectorizer and CountVectorizer from the sklearn module.


### TfidfVectorizer
Converts documents to a matrix of TF-IDF features.

##### Term frequency

$$TF_{word,document} = \frac{\number\_of\_times\_word\_appears\_in\_document}{total\_\number\_of\_words\_in\_document}$$

#### Inverse document frequency

$$ IDF_{word} = \log\left(\frac{total\_\number\_of\_documents}{\number\_of\_documents\_containing\_word}\right) $$

TfidfVectorizer = TF*IDF 

### CountVectorizer
Convert a collection of text to a matrix of token counts.

This program aims to use Logistic Regression and Random Forest models to predict if a given message in the dataset is a spam message or not



## Author info
Bruce Mvubele \
[LinkedIn](https://www.linkedin.com/in/bruce-mvubele-494105143/) \
e-mail: cmvubele@gmail.com
