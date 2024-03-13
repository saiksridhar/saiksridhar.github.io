---
layout: archive
title: "Personal ML and AI Projects"
permalink: /publications/
author_profile: true
---
_________________________________
The following projects are examples of the approach I use for data exploration, pre-processing and model development for professional projects and personal ML/AI bot traders I develop for crypto trading.

_________________________________

## [Drug Classification](https://github.com/saiksridhar/saiksridhar.github.io/blob/master/Drug_Classifiation/MLP%20with%20Keras%20Practice%202.ipynb)
This is a simple drug classification problem using patient health data to then classify the drug they would have recieved. The purpose of this project is to serve as a basic ML template. This includes a number of key techniques that could easily be scaled to more complex data problems. This project explores:

- Exploratory Data Analysis
- Feature engineering using transformers
- Building pipelines of column transformers and classifiers
- Testing multiple ML models (including XGBoost, SVM and Neural Networks
- Using GridSearchCV to tune Neural Network hyperparameters
- Analysing classification output using Confusion Matricies

## [Credit Score Classification](https://github.com/saiksridhar/saiksridhar.github.io/blob/master/Credit_Classification/Credit_Score_Prediction.ipynb)
Credit Scoring enables credit decisioning and pricing (such as interest rates) to support an optimised portfolio for the institution in line with profitablility targets and risk apetite. This is vital to the survival and success of any financial institution which issues lending products.

The primary challenges dealt with in this classification process are data cleansing, imputation and model development. Custom imputers have been developed in this Notebook along with testing of the imputed features during the model training phase. Additionally, various configurations and approaches are taken to develop a predictive neural network model.This project explores:

- Exploratory Data Analysis
- Feature engineering using multiple custom transformers
- Building pipelines of column transformers and classifiers
- Testing multiple ML models (including XGBoost, SVM and Neural Networks
- Using GridSearchCV to tune Neural Network hyperparameters
- Analysing classification output using Confusion Matricies


{::comment}
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{:/comment}
