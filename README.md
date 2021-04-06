# Titanic survivors

This repository is about my first Kaggle (www.kaggle.com) competition. 

## The goal

The main goal was to use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

## The Data

The data to train and evaluate contains 12 columns about the passengers on board (Age, Fare, Name, PassengerID, Survived, among others).

## Learning and Results

During this work, I used data analysis to understand how the data was composed and distributed. And I also worked with a few statistical concepts to generate insights to improve the goal.

For the data analysis, I analyzed and visualized the correlation between variables

### Correlation matrix

![Alt text](./Screenshots/corr.png?raw=true "Corr")

### "Fare" Boxplot

![Alt text](./Screenshots/box_fare.png?raw=true "box_fare")

### Age Histogram

![Alt text](./Screenshots/hist_age.png?raw=true "hist_age")

Some metrics such as standard deviation, min, max, and quartiles of the variable Age and Fare also were evaluated.

For the machine learnings, I ran the following models:

* Tree Classifier
* Random Forest Classifier
* Logistic Regression
* Perceptron
* SGD Classifier

The better result came from the Random Forest Classifier which achieved a <b>score</b> of 0.98, <b>accuracy</b> of 0.8 and <b>recall</b> of 0.73.

In the competition, my model was able to achieve a score of 0.76315 which means that my model predicts the correct answer 76% of the time.

## Conclusion and Final Thoughts

At the end of this project, I noticed that with a simple data analysis and with "untuned" machine learning was possible to achieve goods results. This open space to improve the analysis towards work on
feature engineering to get better models without put a lot of effort into it.

### If you want to see more about this analysis with a little more explanation and graphs about why and how I manipulated the data into the machine learning models, take a look in my notebook.
Any comments or questions are welcome.
