---
layout: post
title: "Automated Focal Loss for Image based Object Detection"
date: 2019-04-19 01:24:52
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Michael Weber, Michael F&#xfc;rst, J. Marius Z&#xf6;llner
mathjax: true
---

* content
{:toc}

##### Abstract
Current state-of-the-art object detection algorithms still suffer the problem of imbalanced distribution of training data over object classes and background. Recent work introduced a new loss function called focal loss to mitigate this problem, but at the cost of an additional hyperparameter. Manually tuning this hyperparameter for each training task is highly time-consuming. 
 With automated focal loss we introduce a new loss function which substitutes this hyperparameter by a parameter that is automatically adapted during the training progress and controls the amount of focusing on hard training examples. We show on the COCO benchmark that this leads to an up to 30% faster training convergence. We further introduced a focal regression loss which on the more challenging task of 3D vehicle detection outperforms other loss functions by up to 1.8 AOS and can be used as a value range independent metric for regression.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09048](http://arxiv.org/abs/1904.09048)

##### PDF
[http://arxiv.org/pdf/1904.09048](http://arxiv.org/pdf/1904.09048)

