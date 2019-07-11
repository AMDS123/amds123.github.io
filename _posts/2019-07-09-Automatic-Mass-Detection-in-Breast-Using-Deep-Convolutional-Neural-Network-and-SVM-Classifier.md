---
layout: post
title: "Automatic Mass Detection in Breast Using Deep Convolutional Neural Network and SVM Classifier"
date: 2019-07-09 21:39:23
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Detection
author: Md. Kamrul Hasan, Tajwar Abrar Aleef
mathjax: true
---

* content
{:toc}

##### Abstract
Mammography is the most widely used gold standard for screening breast cancer, where, mass detection is considered as the prominent step. Detecting mass in the breast is, however, an arduous problem as they usually have large variations between them in terms of shape, size, boundary, and texture. In this literature, the process of mass detection is automated with the use of transfer learning techniques of Deep Convolutional Neural Networks (DCNN). Pre-trained VGG19 network is used to extract features which are then followed by bagged decision tree for features selection and then a Support Vector Machine (SVM) classifier is trained and used for classifying between the mass and non-mass. Area Under ROC Curve (AUC) is chosen as the performance metric, which is then maximized during classifier selection and hyper-parameter tuning. The robustness of the two selected type of classifiers, C-SVM, and \u{psion}-SVM, are investigated with extensive experiments before selecting the best performing classifier. All experiments in this paper were conducted using the INbreast dataset. The best AUC obtained from the experimental results is 0.994 +/- 0.003 i.e. [0.991, 0.997]. Our results conclude that by using pre-trained VGG19 network, high-level distinctive features can be extracted from Mammograms which when used with the proposed SVM classifier is able to robustly distinguish between the mass and non-mass present in breast.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04424](http://arxiv.org/abs/1907.04424)

##### PDF
[http://arxiv.org/pdf/1907.04424](http://arxiv.org/pdf/1907.04424)

