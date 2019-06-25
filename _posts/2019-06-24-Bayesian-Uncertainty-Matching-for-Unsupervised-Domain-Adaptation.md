---
layout: post
title: "Bayesian Uncertainty Matching for Unsupervised Domain Adaptation"
date: 2019-06-24 02:57:22
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Jun Wen, Nenggan Zheng, Junsong Yuan, Zhefeng Gong, Changyou Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adaptation is an important technique to alleviate performance degradation caused by domain shift, e.g., when training and test data come from different domains. Most existing deep adaptation methods focus on reducing domain shift by matching marginal feature distributions through deep transformations on the input features, due to the unavailability of target domain labels. We show that domain shift may still exist via label distribution shift at the classifier, thus deteriorating model performances. To alleviate this issue, we propose an approximate joint distribution matching scheme by exploiting prediction uncertainty. Specifically, we use a Bayesian neural network to quantify prediction uncertainty of a classifier. By imposing distribution matching on both features and labels (via uncertainty), label distribution mismatching in source and target data is effectively alleviated, encouraging the classifier to produce consistent predictions across domains. We also propose a few techniques to improve our method by adaptively reweighting domain adaptation loss to achieve nontrivial distribution matching and stable training. Comparisons with state of the art unsupervised domain adaptation methods on three popular benchmark datasets demonstrate the superiority of our approach, especially on the effectiveness of alleviating negative transfer.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09693](http://arxiv.org/abs/1906.09693)

##### PDF
[http://arxiv.org/pdf/1906.09693](http://arxiv.org/pdf/1906.09693)

