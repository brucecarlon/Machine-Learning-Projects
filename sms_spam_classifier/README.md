# SMS SPAM CLASSIFIER

> Using NLP and machone learning algothrims to classify sms messages as spam


#### Defintions:
 * Spam :\
    Irrelevant or unsolicited messages sent over  the internet, typically to a large number of users, for the purposes of advertising, phishing, spreading malware, etc.
  * Tokenization : \
    Is the process of chanign the representation of words as a string to represent them as numbers.
    

## Description

Using the data from UCL ML Datasets this programs aims to predict if a text is spam or not.

We use two tokenization methods: TfidfVectorizer and CountVectorizer from the sklearn module.


### TfidfVectorizer
Converts documents to a matrix of TF-IDF features.
##### Term frequency
$$TF_{word,document} = \frac{\#\_of\_times\_word\_appears\_in\_document}{total\_\#\_of\_words\_in\_document}$$
#### Inverse document frequency
$$ IDF_{word} = \log\left(\frac{total\_\#\_of\_documents}{\#\_of\_documents\_containing\_word}\right) $$

TfidfVectorizer = TF*IDF 

### CountVectorizer
Convert a collection of text to a matrix of token counts.

This program aims to use Logistic Regression and Random Forest models to predict if a given message in the dataset is a spam message or not

## Data

Data Source: https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection




## Author info
Bruce Mvubele \
[LinkedIn](https://www.linkedin.com/in/bruce-mvubele-494105143/) \
e-mail: cmvubele@gmail.com
