# Bike Sharing Case Study

## Table of Contents
* [Problem Statement](#problem-statement)
* [Steps](#steps)
* [Technologies Used](#technologies-used)
* [Conclusion](#conclusion)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
A US bike-sharing provider BoomBikes wants to understand the factors on which the demand for shared bikes depends.

The company specifically wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Steps
- Reading, understanding and visualizing data
- Preparing data for modelling (train-test split)
- Training the model
- Residual analysis
- Predictions and evaluation on test

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Linear Regression using sklearn, statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusion
- Variables that are significant in predicting the demand for shared bikes are <b>'yr', 'atemp', 'casual', 'rain_or_snow'</b>
- 75% of the data fit the regression model
- Equation of our best-fit line is:
  
  $ cnt = 0.21  \times  yr + 0.46  \times  atemp + 0.32 \times casual - 0.18 \times rain\_or\_snow  $


## Contact
Created by [@scpowar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
