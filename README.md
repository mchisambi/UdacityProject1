# UdacityProject1
First project as first part of Data Scientist Nanodegree
The project seeks to use a public data set re Stroke incidence from Kaggle to answer three questions:
1. Does age play a role in stroke incidence?
2. Is hypertension more likely to lead to strokes?
3. Can we predict who is likely to have a stroke based on their characteristics?

The Python libraries used in this list include pandas, numpy, matplotlib.pyplot, scikit-learn (sklearn), seaborn, missingno, scipy with modules such as LinearRegression, train_test_split, cross_validate, r2_score, mean_squared_error, accuracy_score, plot_confusion_matrix, metrics, pywaffle, SVC.

There is one file in the repository 'strokePrediction.ipynb': this creates an overview of the analysis taken to answer the three questions above. 

The results show that:
1. Increased age is positively associated with stroke (0.25)
2. Hypertension is more likely to lead to stroke (OR  3.698; p-value <0.05)
3. We can predict with 94% accuracy or precision (confusion matrix 0.94)

Acknowledgements:
Data: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset
Code: https://www.kaggle.com/code/bhuvanchennoju/data-storytelling-auc-focus-on-strokes
