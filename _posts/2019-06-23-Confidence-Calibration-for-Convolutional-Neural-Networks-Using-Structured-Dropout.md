---
layout: post
title: "Confidence Calibration for Convolutional Neural Networks Using Structured Dropout"
date: 2019-06-23 04:34:14
categories: arXiv_CV
tags: arXiv_CV CNN Inference Classification Prediction Relation
author: Zhilu Zhang, Adrian V. Dalca, Mert R. Sabuncu
mathjax: true
---

* content
{:toc}

##### Abstract
In classification applications, we often want probabilistic predictions to reflect confidence or uncertainty. Dropout, a commonly used training technique, has recently been linked to Bayesian inference, yielding an efficient way to quantify uncertainty in neural network models. However, as previously demonstrated, confidence estimates computed with a naive implementation of dropout can be poorly calibrated, particularly when using convolutional networks. In this paper, through the lens of ensemble learning, we associate calibration error with the correlation between the models sampled with dropout. Motivated by this, we explore the use of structured dropout to promote model diversity and improve confidence calibration. We use the SVHN, CIFAR-10 and CIFAR-100 datasets to empirically compare model diversity and confidence errors obtained using various dropout techniques. We also show the merit of structured dropout in a Bayesian active learning application.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09551](http://arxiv.org/abs/1906.09551)

##### PDF
[http://arxiv.org/pdf/1906.09551](http://arxiv.org/pdf/1906.09551)

