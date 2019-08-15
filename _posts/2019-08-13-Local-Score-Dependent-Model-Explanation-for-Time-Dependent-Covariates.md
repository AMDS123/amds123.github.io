---
layout: post
title: "Local Score Dependent Model Explanation for Time Dependent Covariates"
date: 2019-08-13 19:46:26
categories: arXiv_AI
tags: arXiv_AI Salient Classification
author: Xochitl Watts, Freddy Lecue
mathjax: true
---

* content
{:toc}

##### Abstract
The use of deep neural networks to make high risk decisions creates a need for global and local explanations so that users and experts have confidence in the modeling algorithms. We introduce a novel technique to find global and local explanations for time series data used in binary classification machine learning systems. We identify the most salient of the original features used by a black box model to distinguish between classes. The explanation can be made on categorical, continuous, and time series data and can be generalized to any binary classification model. The analysis is conducted on time series data to train a long short-term memory deep neural network and uses the time dependent structure of the underlying features in the explanation. The proposed technique attributes weights to features to explain an observations risk of belonging to a class as a multiplicative factor of a base hazard rate. We use a variation of the Cox Proportional Hazards regression, a Generalized Additive Model, to explain the effect of variables upon the probability of an in-class response for a score output from the black box model. The covariates incorporate time dependence structure in the features so the explanation is inclusive of the underlying time series data structure.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04839](http://arxiv.org/abs/1908.04839)

##### PDF
[http://arxiv.org/pdf/1908.04839](http://arxiv.org/pdf/1908.04839)

