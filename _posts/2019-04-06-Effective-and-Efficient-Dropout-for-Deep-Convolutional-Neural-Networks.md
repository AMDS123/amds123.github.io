---
layout: post
title: "Effective and Efficient Dropout for Deep Convolutional Neural Networks"
date: 2019-04-06 09:17:51
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Optimization Deep_Learning
author: Shaofeng Cai, Jinyang Gao, Meihui Zhang, Wei Wang, Gang Chen, Beng Chin Ooi
mathjax: true
---

* content
{:toc}

##### Abstract
Machine-learning-based data-driven applications have become ubiquitous, e.g., health-care analysis and database system optimization. Big training data and large (deep) models are crucial for good performance. Dropout has been widely used as an efficient regularization technique to prevent large models from overfitting. However, many recent works show that dropout does not bring much performance improvement for deep convolutional neural networks (CNNs), a popular deep learning model for data-driven applications. In this paper, we formulate existing dropout methods for CNNs under the same analysis framework to investigate the failures. We attribute the failure to the conflicts between the dropout and the batch normalization operation after it. Consequently, we propose to change the order of the operations, which results in new building blocks of CNNs.Extensive experiments on benchmark datasets CIFAR, SVHN and ImageNet have been conducted to compare the existing building blocks and our new building blocks with different dropout methods. The results confirm the superiority of our proposed building blocks due to the regularization and implicit model ensemble effect of dropout. In particular, we improve over state-of-the-art CNNs with significantly better performance of 3.17%, 16.15%, 1.44%, 21.46% error rate on CIFAR-10, CIFAR-100, SVHN and ImageNet respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03392](http://arxiv.org/abs/1904.03392)

##### PDF
[http://arxiv.org/pdf/1904.03392](http://arxiv.org/pdf/1904.03392)

