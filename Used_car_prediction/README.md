# Used car prediction

**Description**: 
Indonesia used car market have been growing fast in the last few years. In 2025,
used car sold twice as much as new car. This new market shift is caused by 
the rise of new online used vehicle-oriented marketplace and economic downturn.

But how do people decide what's the best price for a used car?


**Data Source**: 
Kaggle uploaded by Indra 
(https://www.kaggle.com/datasets/indraputra21/used-car-listings-in-indonesia/data)

**Skills**: 
Data cleaning, exhaustive search, OLS regression, regression tree, and random forest.

**Tools**: 

R: tidyverse, dplyr, olsrr, leaps, lmtest, plm, MASS, caret, and randomForest. 

**Findings**:

Variable Importance
Engine capacity, manual/automatic transmission, and brand popularity are the top significant and important variables in predicting used car price. 
Hence, Indonesian considers those variables to be top characteristic to keep in mind when deciding  used car price. 

Model performance 
Random Forest, WLS model, and double log model are the top model to predict used car price. 
Surprisingly, WLS and double log model have higher prediction performance than regression tree. This is unusual, considering previous test have shown that the model might has non-linear relationship that hinders regression performance. 
But this might show that the Remsey RESET test is biased due to heteroscedasticity. 
