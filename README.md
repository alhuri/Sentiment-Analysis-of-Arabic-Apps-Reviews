# Sentiment-Analysis-of-Arabic-Apps-Reviews
Sentiment analysis is useful in review monitoring to automatically characterize the overall feeling or mood of consumers as reflected in web toward a specific App. Tracking app problems depending on reviews sentiment continuously is useful in the process of improving applications and their services. This form of analysis has been widely adopted in customer relations management, especially in the context of complaint management.

## Value Proposition
User reviews in app stores are considered very rich maintenance information texts that developers need to know. A huge number of reviews of apps contain requirements details such as bugs or problems, evaluation of user experience with some features, suggestions for improvements, and ideas for new features.

## Dataset Information
Arb-AppsReview is the first Arabic dataset designed to capture popular review on Google Play store 51k Arabic reviews related to 6 Saudi governmental services apps,
namely: Tawakkalna, Tetaman, Tabaud, Sehhaty, Mawid, and Sehhah. That can provide an overview of the types of requirements issues users report on the apps. 
*View the data* [here](https://github.com/Arb-AppsReview/Arb-AppsReview)

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
- Reducing the work needed to analyze and extract valuable content from mobile app reviews
- Get an overall recognition of user requirements and technical issues feedbacks to avoid major programming problems and provide useful knowledge relevant to the app's improvement
- Discovering packages and functions in python for data manipulation, EDA, and machine learning.
- Evaluate different models preformance.

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
``
## Future Work
- study the gap of the user requirements needs between males andfemales and study functional and non-functional issues that every category notes and
cares about improving

## References
Al-Sarem, Mohammed & Saeed, Faisal & Alshamani, Maha. (2021). Design of an Arabic Google Play Store User Reviews Dataset for Detecting Apps Requirements Issues. 
