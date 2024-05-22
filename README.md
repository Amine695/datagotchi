# Datagotchi

## What if your lifestyle made it possible to predict your political allegiance?


### Web Application whose aim is to predict the intentions of votes based on lifestyle using ML models

Here is the [application](https://datagotchi.com/) you can try ! 

### Introduction
Datagotchi is a fun and educational application that engages the user in design
interactive version of an avatar representing its lifestyle habits, and which then aims to predict attitudes and
social behaviors. Based on individual characteristics linked to lifestyle habits, the most
recent release of Datagotchi aimed to predict users' voting intention for Quebec general elections of October 3, 2022.


### Goal of this project
In this academic project, we aim to study the potential of Datagotchi data to make electoral predictions at the constituency level. Among other things, we will have to determine the types of population that will have been able to correctly predict the results of past elections.
The identification of these populations could subsequently make it possible to make electoral predictions.

More precisely, a type of population that generally makes good predictions, that is to say that the
results that they announce during a survey prove to be true, could have an opinion (or a weight) of greater importance than populations predicting outcomes that turn out to be wrong.

### Data used
In particular, we will have access to the data collected by the Datagotchi application, namely:
-  Identification data of the individuals surveyed (gender, age group, country/language of origin,
origin, sexual orientation, city, district, etc.)
- Their habits and lifestyle (animals, alcohol consumption, clothing style, practices
sports, ...)
- Electoral predictions for each party by constituency
- Individual predictions of citizens of the winning party
- Real results

This dataset has thirty variables and around 70,000 observations


### Methods

In order to address this issue, we would start by exploring, analyzing and cleaning the data provided by the Datagotchi application. This first phase of analysis could allow us to fully understand this data, to identify initial trends and to determine certain influential characteristics in terms of electoral predictions.

Secondly, we would be interested in the application of different machine learning models in a binary classification approach in order to identify the characteristics impacting the correct prediction, or not, of a party by a citizen. These approaches would also allow us to conclude regarding the prediction potential of the data collected by Datagotchi based on
results obtained by our models. In this approach, the performance criteria considered would be precision, recall or even the F-score.


For this study, we could consider the following models (as an example):
— Logistic regression
— A non-parametric method like k-NN
— A deep learning method
Furthermore, these models would be subject to different hyperparameters (search by grid in particular),
different data pre-processing (normalization, encoding, etc.) and different combinations
of variables in order to identify the association presenting the best results.


### Authors
Amine Berbagui <br>
David-Alexandre Duclos <br>
Yannis Canton