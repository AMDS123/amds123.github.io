---
layout: post
title: "Bootstrap Model Ensemble and Rank Loss for Engagement Intensity Regression"
date: 2019-07-08 06:54:47
categories: arXiv_CV
tags: arXiv_CV Regularization RNN Prediction
author: Kai Wang, Jianfei Yang, Da Guo, Kaipeng Zhang, Xiaojiang Peng, Yu Qiao
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents our approach for the engagement intensity regression task of EmotiW 2019. The task is to predict the engagement intensity value of a student when he or she is watching an online MOOCs video in various conditions. Based on our winner solution last year, we mainly explore head features and body features with a bootstrap strategy and two novel loss functions in this paper. We maintain the framework of multi-instance learning with long short-term memory (LSTM) network, and make three contributions. First, besides of the gaze and head pose features, we explore facial landmark features in our framework. Second, inspired by the fact that engagement intensity can be ranked in values, we design a rank loss as a regularization which enforces a distance margin between the features of distant category pairs and adjacent category pairs. Third, we use the classical bootstrap aggregation method to perform model ensemble which randomly samples a certain training data by several times and then averages the model predictions. We evaluate the performance of our method and discuss the influence of each part on the validation dataset. Our methods finally win 3rd place with MSE of 0.0626 on the testing set.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03422](http://arxiv.org/abs/1907.03422)

##### PDF
[http://arxiv.org/pdf/1907.03422](http://arxiv.org/pdf/1907.03422)

