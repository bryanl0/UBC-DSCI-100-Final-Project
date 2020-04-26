# UBC DSCI 100 2018W Final Project
This is my group's final project in the 2018W2 offering of the DSCI 100 course.

Essentially, we sought to determine the optimal first medical test to perform when diagnosing for Chronic Kidney Disease (CKD). The data we worked with was a tabular summary of the results arising from various medical tests performed on 400 individuals, as well as a column indicating whether each individual had CKD. 

In formulating our question of an optimal first-test, we appealed to Bayes' Rule to make the argument that the first medical test performed does not have to be incontrovertibly accurate in predicting CKD, as further testing would most likely be required anyway given the relatively low prevalence of CKD among the general public. Instead, we sought to seek an optimal balance between accuracy and time & effort in the first medical test performed. The test would need to have reasonably high accuracy so as to be able to reliably serve the purpose of raising an alarm for further testing, but also preferably quick and easy for the patient. Basically, we wanted to determine the easiest medical test to perform that was also "accurate enough."

In attempting to answer our question, we performed Exploratory Data Analysis (EDA), KNN classification with hyperparameter tuning by Cross-Validation, as well as a sort of primitive feature selection whereby we group the features into the medical tests from which they arise.

In the end, our findings did not leave us feeling very confident that our results could be generalized, as we were able to obtain 100% test accuracy with several combinations of features. We suspected that our dataset was too small. However, we were able to provide a rudimentary answer to our original question and consequently suggest Urinalysis as the optimal first-test in diagnosing for CKD, since it is relatively cheap and easy to perform, and exceptionally accurate (achieving a 98.7% test accuracy).

By Violet, Bryan, Justin
