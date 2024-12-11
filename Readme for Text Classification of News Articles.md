
## Text Classification of News Articles 

The goal of the Text Classification of News Articles project is to use machine learning to automatically classify news articles into predetermined groups. Given the increasing amount of news content that is generated every day, manual classification can be laborious and prone to mistakes. This project uses natural language processing (NLP) techniques to accurately identify news stories, offering a scalable and effective solution.

The BBC News Classification Dataset, which includes labelled news stories in several categories, was used to create the project dataset. Text material and the associated category are included in every article.

    Preprocessing Text:
        Important NLP preprocessing steps were put into practice:
            eliminating punctuation and stopwords.
            Lemmatisation, stemming, and tokenisation.
            Text is being converted to lowercase for consistency.
            use methods such as TF-IDF (Term Frequency-Inverse Document Frequency) to convert text data into numerical characteristics.

    Modelling: A variety of machine learning models were tested:
            Regression using Logistic
            The Random Forest Classifier
            Classifier Using Decision Trees
        Model performance was compared using assessment criteria such F1-score, recall, accuracy, and precision.

 ## Target of the Project

This project's major goal is to create a proof-of-concept for organisations, journalists, and content aggregators looking to automate news item classification. This may help:

    News agencies can quickly organise stories into predetermined categories to improve content management.
    Readers: Create personalised suggestions by categorising news articles based on their interests.
    Researchers: Serve as a basic study for the implementation of NLP-based text classification.

Furthermore, the project is intended to help aspiring data scientists and NLP aficionados learn and practise constructing end-to-end machine learning pipelines for text classification problems.




## Acknowledgements

 - [scikit-learn](https://scikit-learn.org/stable/):For building and evaluating machine learning models.
 - [Pandas](https://pandas.pydata.org/): For data manipulation and preprocessing.
 - [matplotlib](https://matplotlib.org/): For visualizing data and results.



## Appendix

Any additional information goes here

Dataset : The dataset used in this project consists of BBC News articles, each labeled with one of the five categories.

The following preprocessing steps were performed on the dataset:

Sure, here’s a concise one-liner for each preprocessing step:
   
   Lowercase Text: To preserve uniformity, convert all text to lowercase.
   Strip out HTML tags to tidy up the text.
   Remove URLs to focus on text content.
   To standardize the content, remove any punctuation marks.
 Handling StopWords: Remove typical stop words that do not add sense.
Tokenization is dividing text into individual words or tokens.
 
 Model Used:
 Random Forest,
 Decision Trees,
 Logistic Regression




## Documentation

[Documentation](https://docs.google.com/document/d/1K_4t7x6qFdL-CkCRzLC34EL_V5osfc5vfjoE-Oa9_VQ/edit?tab=t.0)


## Environment Details


Python version: 3.8+
Key Libraries: scikit-learn (1.2.2), pandas (1.4.0), nltk (3.6.7)
