
Text Classification of News Articles 

Text Classification of News Articles is about classifying the news articles into its particular categories For instance if the news article is related to sports category then model gets classified as Sports and if the news article related to politics then model classify it as politics



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