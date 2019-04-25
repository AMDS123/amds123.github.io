---
layout: post
title: "KFHE-HOMER: Kalman Filter-based Heuristic Ensemble of HOMER for Multi-Label Classification"
date: 2019-04-23 22:10:50
categories: arXiv_AI
tags: arXiv_AI Classification
author: Arjun Pakrashi, Brian Mac Namee
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-label classification allows a datapoint to be labelled with more than one class at the same time. Ensemble methods generally perform much better than single classifiers. Except bagging style ensembles like ECC, RAkEL, in multi-label classification, other ensemble methods have not been explored much. KFHE (Kalman Filter-based Heuristic Ensemble), is a recent ensemble method which uses the Kalman filter to combine several models. KFHE views the final ensemble to be learned as a state to be estimated which it estimates using multiple noisy "measurements". These "measurements" are essentially component classifiers trained under different settings. This work extends KFHE to multi-label domain by proposing KFHE-HOMER which enhances the performance of HOMER using the KFHE framework. KFHE-HOMER sequentially trains multiple HOMER classifiers using weighted training datapoints and random hyperparameters. These models are considered as measurements and their related error as the uncertainty of the measurements. Then the Kalman filter framework is used to combine these measurements to get a more accurate estimate. The method was tested on 10 multi-label datasets and compared with other multi-label classification algorithms. Results show that KFHE-HOMER performs consistently better than similar multi-label ensemble methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10552](http://arxiv.org/abs/1904.10552)

##### PDF
[http://arxiv.org/pdf/1904.10552](http://arxiv.org/pdf/1904.10552)

