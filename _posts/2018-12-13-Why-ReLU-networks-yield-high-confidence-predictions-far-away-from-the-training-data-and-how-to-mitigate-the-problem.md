---
layout: post
title: "Why ReLU networks yield high-confidence predictions far away from the training data and how to mitigate the problem"
date: 2018-12-13 22:52:42
categories: arXiv_CV
tags: arXiv_CV Adversarial Optimization Classification Prediction
author: Matthias Hein, Maksym Andriushchenko, Julian Bitterwolf
mathjax: true
---

* content
{:toc}

##### Abstract
Classifiers used in the wild, in particular for safety-critical systems, should not only have good generalization properties but also should know when they don't know, in particular make low confidence predictions far away from the training data. We show that ReLU type neural networks which yield a piecewise linear classifier function fail in this regard as they produce almost always high confidence predictions far away from the training data. For bounded domains like images we propose a new robust optimization technique similar to adversarial training which enforces low confidence predictions far away from the training data. We show that this technique is surprisingly effective in reducing the confidence of predictions far away from the training data while maintaining high confidence predictions and similar test error on the original classification task compared to standard training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05720](http://arxiv.org/abs/1812.05720)

##### PDF
[http://arxiv.org/pdf/1812.05720](http://arxiv.org/pdf/1812.05720)

