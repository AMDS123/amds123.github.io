---
layout: post
title: "Learning to Find Correlated Features by Maximizing Information Flow in Convolutional Neural Networks"
date: 2019-06-30 09:58:18
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Image_Classification Classification Prediction
author: Wei Shen, Fei Li, Rujie Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Training convolutional neural networks for image classification tasks usually causes information loss. Although most of the time the information lost is redundant with respect to the target task, there are still cases where discriminative information is also discarded. For example, if the samples that belong to the same category have multiple correlated features, the model may only learn a subset of the features and ignore the rest. This may not be a problem unless the classification in the test set highly depends on the ignored features. We argue that the discard of the correlated discriminative information is partially caused by the fact that the minimization of the classification loss doesn't ensure to learn the overall discriminative information but only the most discriminative information. To address this problem, we propose an information flow maximization (IFM) loss as a regularization term to find the discriminative correlated features. With less information loss the classifier can make predictions based on more informative features. We validate our method on the shiftedMNIST dataset and show the effectiveness of IFM loss in learning representative and discriminative features.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00348](http://arxiv.org/abs/1907.00348)

##### PDF
[http://arxiv.org/pdf/1907.00348](http://arxiv.org/pdf/1907.00348)

