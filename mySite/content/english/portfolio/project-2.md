---
title: "Predict Patient Survival"
date: 2022-12-05T12:14:34+06:00
image: "images/portfolio/AML.JPG"
categories: ["machine learning"]
description: "This is meta description."
draft: false
project_info:
- name: "Github Link"
  icon: "fas fa-link"
  content: "https://github.com/tzhou19/AML_project"
---

Patient survival prediction model trained using MIT’s GOSSIS (Global Open Source Severity of Illness Score) dataset. This dataset includes a number of factors collected from admitted patients, including whether the patient died during hospitalization. This dataset was leveraged in order to characterize the predictors for in-hospital mortality through the creation of models using a variety of machine learning techniques. We also compared these models and identified which technique is most suitable for this classification task.


#### Project Details

Different machine learnig techniques were applied including SVM, logistic regression, trees, neural networks. The highest accuracy was achieved by the random forest model, with an accuracy of 0.930, with logistic regression, neural network, and HistGradientBoostingClassifier achieving similar accuracy values. LinearSVC and SVC with the RBF kernel achieved lower accuracy values of 0.802 and 0.857, respectively. However, LinearSVC and SVC achieved the highest values for AUC and average precision, and SVC also achieved the highest F1- score. The neural network achieved a relatively high AUC and F1-score, while obtaining the lowest average precision. F1-scores were relatively close for each of the models, excluding logistic regression which achieved the lowest F1-score. 
When comparing the two best tree-based models, HistGradientBoostingClassifier performed better in all metrics over the random forest model, excluding accuracy which was only slightly lower for HistGradientBoostingClassifier. When comparing the two best SVM models, SVC with the RBF kernel seemed to have a better tradeoff compared to LinearSVC, since SVC achieved a greater than 5% increase in accuracy, a similar AUC value, and a higher F1 score, although it also had a lower average precision value.
