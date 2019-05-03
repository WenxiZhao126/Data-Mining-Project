### Data-Mining-Project

### UVA MSDS 2018 Fall 2018

### Fang You (fy6vj)，Wenxi Zhao (wz8nx), Shaoran Li (sl4bz)

### Overview:

### Problem Description

While many public datasets online provide Apple App Store data, there are not many counterpart datasets available for Google Play Store Apps anywhere on the web. The Play Store Apps data has enormous potential to drive App-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market. 

Our project analyzes the Android app market using a Kaggle-hosted, web scraped dataset which describes 10k Google Play Store apps. We will do Exploratory Data Analysis, supplemented by some empirically competent statistical models to explore which features affect the rating of apps. We can also use our model to make predictions on app "Rating" given their features. 


### Objectives and Metrics

The objective of this project is to identify the relevant predictors that correlate to the "Rating" of the apps and to develop a model that could predict "Rating" while minimizing mean squared error and constraining variance. We are also studying patterns in various types of predictors and use these patterns to find correlations between predictors and response variable(i.e. "Rating"). There are two types of predictions that could be made based on our studies. One type of prediction is to forecast the potential popularity and ranking of apps in the near future based on existing metrics. Another type of prediction is to determine how app developers can adjust metrics available to them to maximize apps' probability of earning high rankings and popularity. 

The metrics we can use to make such predictions are Apps’ Category, Rating, Reviews, Size, (no. of) Installs, Type (paid or free), Price, Content Rating, Genre, Last Updated, Current Ver, Android Ver, Translated_Review, Sentiment, Sentiment_Polarity and Sentiment Subject. Among these metrics, there are only a few metrics such as Type, Price and those associated with version that could be controlled by App developers. As such, the objectives of our second type of prediction would be limited since App developers can only manipulate a limited number of predictor metrics to affect their Apps’ popularity. Nonetheless, we will be able to use these variables to construct multiple models and compare their effectiveness to help us make our first type of prediction. 

### Content:

./Data: Google Play Store apps data from Kaggle
