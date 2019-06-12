---
layout: post
title: "Data augmentation instead of explicit regularization"
date: 2019-06-11 13:11:51
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge CNN Gradient_Descent
author: Alex Hern&#xe1;ndez-Garc&#xed;a, Peter K&#xf6;nig
mathjax: true
---

* content
{:toc}

##### Abstract
Modern deep artificial neural networks have achieved impressive results through models with orders of magnitude more parameters than training examples which control overfitting with the help of regularization. Regularization can be implicit, as is the case of stochastic gradient descent and parameter sharing in convolutional layers, or explicit. Explicit regularization techniques, most common forms are weight decay and dropout, have proven successful in terms of improved generalization, but they blindly reduce the effective capacity of the model, introduce sensitive hyper-parameters and require deeper and wider architectures to compensate for the reduced capacity. In contrast, data augmentation techniques exploit domain knowledge to increase the number of training examples and improve generalization without reducing the effective capacity and without introducing model-dependent parameters, since it is applied on the training data. In this paper we systematically contrast data augmentation and explicit regularization on three popular architectures and three data sets. Our results demonstrate that data augmentation alone can achieve the same performance or higher as regularized models and exhibits much higher adaptability to changes in the architecture and the amount of training data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.03852](http://arxiv.org/abs/1806.03852)

##### PDF
[http://arxiv.org/pdf/1806.03852](http://arxiv.org/pdf/1806.03852)

