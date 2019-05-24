---
layout: post
title: "Generative Imputation and Stochastic Prediction"
date: 2019-05-22 19:29:46
categories: arXiv_AI
tags: arXiv_AI Face Classification Prediction
author: Mohammad Kachuee, Kimmo Karkkainen, Orpaz Goldstein, Sajad Darabi, Majid Sarrafzadeh
mathjax: true
---

* content
{:toc}

##### Abstract
In many machine learning applications, we are faced with incomplete datasets. In the literature, missing data imputation techniques have been mostly concerned with filling missing values. However, the existence of missing values is synonymous with uncertainties not only over the distribution of missing values but also over target class assignments that require careful consideration. The objectives of this paper are twofold. First, we proposed a method for generating imputations from the conditional distribution of missing values given observed values. Second, we use the generated samples to estimate the distribution of target assignments given incomplete data. In order to generate imputations, we train a simple and effective generator network to generate imputations that a discriminator network is tasked to distinguish. Following this, a predictor network is trained using imputed samples from the generator network to capture the classification uncertainties and make predictions accordingly. The proposed method is evaluated on CIFAR-10 image dataset as well as two real-world tabular classification datasets, under various missingness rates and structures. Our experimental results show the effectiveness of the proposed method in generating imputations, as well as providing estimates for the class uncertainties in a classification task when faced with missing values.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09340](http://arxiv.org/abs/1905.09340)

##### PDF
[http://arxiv.org/pdf/1905.09340](http://arxiv.org/pdf/1905.09340)

