# Income Prediction 

## Goal: 
This project focuses on developing a machine learning model--logistic regression--that uses predictors, such as an individual's demographics(e.g. native country, age, occupation, net capital), to predict whether they make an income of over $50,000 or below.

## Tools:
* Data processing:

    * Pandas and Numpy

* Data visualization:

    * Matplotlib

* Data modeling:

    * Scikit-learn

* Version control:

    * Git and Github

## Result:
* I was able to create a Logistic Regression model that yields an accuracy result of 80%.
* I optimized the model using cross-validation, L1 and L2 regularlization, and scaling data.
* Interstingly, some variables like race and occupation are not statistically significant in predicting whether a person makes over $50k or not while factors like age, net-capital, and education level significantly predict income level. This makes sense because factors like age and education level enhance a person's experience and ability that could make themselves become a valuable asset to the company so therefore they get paid more as a result of that and not because of the position they hold.

## Limitation:
* This data is limited because of the old year it was created and so the prediction might not be relevant to today's income prediction standards
* Despite the optimization techniques, it was hard to see any significant increase in the accuracy metrics so there's definitely more room to investigate on other techniques to increase the accuracy level.

## Data set source:
* This data set was obtained from UC Irvine's Machine Learning Repository (https://archive.ics.uci.edu/dataset/2/adult)

* Becker,Barry and Kohavi,Ronny. (1996). Adult. UCI Machine Learning Repository. https://doi.org/10.24432/C5XW20.
