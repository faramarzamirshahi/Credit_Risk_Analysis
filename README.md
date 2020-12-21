# Credit_Risk_Analysis
# Overview of the analysis
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans.<br>
We are going to use a number of different techniquest to train and evaluate models with unbalanced data.
# Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores<br>
of all six machine learning models. Use screenshots of you outputs to support your results
The below chart shows the confusion matrix and the related metrics<br>
![confusion matrix](Resources/confusionMatrixChart.png)
![All models metrics](Resources/Metrics.png)
* We see that all the models score high on low_risk prediction (high precision)<br>
* We see that all the models peform poorly on high_risk prediction (low precision)
* The ensemble models work fairly well on high_risk prediction<br>


# Summary

Summarize the results of the machine learning models,<br>
* The best model overall on both high and low risk prediction is Easy Ensemble Classifier<br>
