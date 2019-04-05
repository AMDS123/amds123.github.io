---
layout: post
title: "Towards Resisting Large Data Variations via Introspective Learning"
date: 2019-04-03 22:41:49
categories: arXiv_CV
tags: arXiv_CV Embedding CNN Classification
author: Yunhan Zhao, Ye Tian, Wei Shen, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Learning deep networks which can resist large variations between training and testing data are essential to build accurate and robust image classifiers. Towards this end, a typical strategy is to apply data augmentation to enlarge the training set. However, standard data augmentation is essentially a brute-force method which is inefficient, as it performs all the pre-defined transformations to every training sample. In this paper, we propose a principled approach to train networks with significantly improved resistance to large variations between training and testing data. This is achieved by embedding a learnable transformation module into the introspective network, which is a convolutional neural network (CNN) classifier empowered with generative capabilities. Our approach alternatively synthesizes pseudo-negative samples with learned transformations and enhances the classifier by retraining it with synthesized samples. Experimental results verify that our approach significantly improves the ability of deep networks to resist large variations between training and testing data and achieves classification accuracy improvements on several benchmark datasets, including MNIST, affNIST, SVHN, CIFAR-10 and miniImageNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.06447](http://arxiv.org/abs/1805.06447)

##### PDF
[http://arxiv.org/pdf/1805.06447](http://arxiv.org/pdf/1805.06447)

