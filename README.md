# Sentiment-Analysis-of-Arabic-Apps-Reviews
Sentiment analysis is useful in review monitoring to automatically characterize the overall feeling or mood of consumers as reflected in web toward a specific App whether they are viewed positively or negatively on the web.This form of analysis has been widely adopted in customer relations management, especially in the context of complaint management.


## Dataset Information
An Arabic dataset contains around 51,000 user reviews from 6 applications retrieved from the google play store
View the data [here](https://github.com/Arb-AppsReview/Arb-AppsReview)

### Data Dictionary

# `apps_ar_reviews_dataset.csv`

|variable  |class     |description |
|:---------|:---------|:-----------|
|UserName   |character | The name of the user displayed on app store  |
|firstName |character | The first name of the user displayed on app store  |
|Review  |character | The textual review of the app given by each user |
|Score |integer   | The score fiven by the user(1 is better than 100) |
|Date/Time   |time    | The time and date of the posted review |
|thumbsUp   |integer   | 0 means no thumsup while 1 means the user gave the app a thumbsup     |
|app      |character   | The name of the app |
|lan_review      |character   | Language used to write the review|
|Gender       |character    | Gender refers to the characteristics of women, men, girls and boys that are socially constructed. |
|ReviewLength |integer    | The number of character in the review |
|words_count |integer    | The number of words in the review |
|Polarity sentiment |integer    | It is the expression that determines the sentimental of an opinion that can be (Positive, Negative, or Neutral) |

## Description

Using a simple python script, the dataset is explored to present the most interesting and useful insights along with the best machine learning model.
### Goals
- Presenting findings gathered from analysis in a report format.
- Discovering packages and functions in python for data manipulation, EDA, word embedding, and machine learning.
- Evaluate diffirent models preformance.

## Content 

```bash
./
│   README.md
│   
└───data/
│   │   apps_ar_reviews_dataset.csv
|   |   Clean_apps_ar_reviews.csv
│   
└───presentation.pptx
│   
└───src/
    │   Data_Cleaning_of_Reviews.ipynb
    |   Visualization_of_Reviews.ipynb
```

## Used Libraries
- 
