---

description: "Python Project"
featured_image: "/images/p2.jpg"
tags: []
title: "Bankruptcy Prediction"
---
In our recent study, we undertook an exhaustive exploration of bankruptcy prediction, a binary classification task, using a dataset sourced from 'data.csv'. The primary objective was to accurately forecast instances of bankruptcy, given the observed features. The dataset, as per preliminary inspection, was marked by a significant class imbalance, highlighting a smaller proportion of bankrupt cases.

Our methodology comprised various phases: initial data inspection, preprocessing (which included scaling of features using the StandardScaler), and a systematic partitioning of the data into training and testing sets. Both scaled and original data were utilized for experimentation.

The machine learning journey involved the application and evaluation of multiple classifiers. We started with a Decision Tree model, assessing its performance using confusion matrices and associated metrics. This was succeeded by experiments with the Random Forest classifier, which included both default and hyperparameter-tuned models. A subsequent GridSearchCV aided in identifying the most optimal parameters for the Random Forest model. Continuing our classifier evaluations, we further incorporated Gradient Boosting and Extra Trees classifiers, examining their performances in similar fashion.

Across all models, performance was benchmarked using a range of metrics, including the F1 score, to account for the imbalanced nature of the dataset. This rigorous approach aimed to pinpoint the most effective and efficient machine learning model for bankruptcy prediction from the provided dataset. Further analyses and extended datasets may be considered to enhance and solidify the findings of this study.

[Click here to Github repo](https://github.com/Happpppppkk/ML/blob/main/Assignment%205-Bankruptcy%20Prediction.ipynb)