---
layout: post
title: "Interpreting a Recurrent Neural Network Model for ICU Mortality Using Learned Binary Masks"
date: 2019-05-23 18:41:09
categories: arXiv_AI
tags: arXiv_AI Salient Sparse RNN Prediction
author: Long V. Ho, Melissa D. Aczon, David Ledbetter, Randall Wetzel
mathjax: true
---

* content
{:toc}

##### Abstract
An attribution method was developed to interpret a recurrent neural network (RNN) trained to predict a child's risk of ICU mortality using multi-modal, time series data in the Electronic Medical Records. By learning a sparse, binary mask that highlights salient features of the input data, critical features determining an individual patient's severity of illness could be identified. The method, called Learned Binary Masks (LBM), demonstrated that the RNN used different feature sets specific to each patient's illness; and further, the features highlighted aligned with clinical intuition of the patient's disease trajectories. LBM was also used to identify the most salient features across the model, analogous to "feature importance" computed in the Random Forest. This measure of the RNN's feature importance was further used to select the 25% most used features for training a second RNN model. Interestingly, but not surprisingly, the second model maintained similar performance to the model trained on all features. LBM is data-agnostic and can be used to interpret the predictions of any differentiable model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09865](http://arxiv.org/abs/1905.09865)

##### PDF
[http://arxiv.org/pdf/1905.09865](http://arxiv.org/pdf/1905.09865)

