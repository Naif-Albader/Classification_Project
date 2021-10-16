
# Sentiment Analysis of IMDB Movie Reviews



## Abstract
filter to the films reviews, based on Positive/Negative reviews
## Design
first dataset is scrapped from the IMDB website.</br>
second is from Kaggle.


## Scope of the work

> Number of features:  5 features/Columns

> Number of rows: Approx.: 60k rows

> Names of columns with description and type:

| Field Name | Description                                                                      |
|-------------|---------------------------------------------------------------------------------|
| Review|      Review of the Movie from a specific user                                              |
| Rating      | Rating of the movie ouf of 10                                   |                                 |
| date        | date of the review                                            |
| like        | how many person liked/agreed with the review                                                             |
| dislike     | how many person disliked/disagreed with the review                                          |






## Algorithms

*Data gathering*:
> 1) Web scrapped the data from IMDB website
> 2) helper tools:
> >     1- BeautifulSoup
> >     2- Selenium

*Data cleaning*:
> 1) Deleteing the duplicated data points
> 2) Deleting Stopwords,html tags,emojis,URL's,Symbols,

*Data validation*:
> 1) Checking no nulls

*feature engineering*:
</br>
Features added:
 > 1) Only considered Rating >7 and Rating <5
 > 2)  Dropped Date,Like,Rating
 > 3)Added Label column “sentiment”,0 1
 
 Model Training &  Evaluation </br>
Data split:</br>
 >  Training: 36k data point</br>
 >  Validation: 12k data point </br>
 >  Testing: 12k data point

Model used: 
> 1) The following models are used: <br>
> 1.1) Logistic regression (Baseline) <br>
> 1.2) MultinomialNB <br>
> 1.3) Random forest <br>
> 1.4) XGboost <br>
> 1.4)DecisionTreeClassifier<br>
> 1.5) BaggingClassifier
>The best found was BaggingClassifier achieving F1 score of 0.884







The main technologies and libraries that will be used are:
Technologies:
> - Python
> - Jupyter Notebook
> - HTML/CSS
> - Flask

Libraries:
> - Pandas
> - pickle
> - BeautifulSoup and selenium
> - OS
> - Matplotlib
> - Seaborn
> - NumPy
> - Sklearn
Processing tools: 
> Google Colab

## Communication
Findings: </br>
 
 <img width="383" alt="image" src="https://user-images.githubusercontent.com/63314269/137586228-02433edb-1236-4909-8657-9bd69a9b5d74.png">
 </br>
 
 <img width="445" alt="image" src="https://user-images.githubusercontent.com/63314269/137586249-ff9c052a-9abb-46de-8760-8dbd64c2ba3e.png">
</br>

<img width="426" alt="image" src="https://user-images.githubusercontent.com/63314269/137586262-58f64410-5b94-46a7-91bb-399aa58e36bc.png">

 

