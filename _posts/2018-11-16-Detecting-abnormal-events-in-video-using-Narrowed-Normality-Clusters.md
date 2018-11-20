---
layout: post
title: "Detecting abnormal events in video using Narrowed Normality Clusters"
date: 2018-11-16 08:59:19
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Radu Tudor Ionescu, Sorina Smeureanu, Marius Popescu, Bogdan Alexe
mathjax: true
---

* content
{:toc}

##### Abstract
We formulate the abnormal event detection problem as an outlier detection task and we propose a two-stage algorithm based on k-means clustering and one-class Support Vector Machines (SVM) to eliminate outliers. In the feature extraction stage, we propose to augment spatio-temporal cubes with deep appearance features extracted from the last convolutional layer of a pre-trained neural network. After extracting motion and appearance features from the training video containing only normal events, we apply k-means clustering to find clusters representing different types of normal motion and appearance features. In the first stage, we consider that clusters with fewer samples (with respect to a given threshold) contain mostly outliers, and we eliminate these clusters altogether. In the second stage, we shrink the borders of the remaining clusters by training a one-class SVM model on each cluster. To detected abnormal events in the test video, we analyze each test sample and consider its maximum normality score provided by the trained one-class SVM models, based on the intuition that a test sample can belong to only one cluster of normality. If the test sample does not fit well in any narrowed normality cluster, then it is labeled as abnormal. We compare our method with several state-of-the-art methods on three benchmark data sets. The empirical results indicate that our abnormal event detection framework can achieve better results in most cases, while processing the test video in real-time at 24 frames per second on a single CPU.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1801.05030](http://arxiv.org/abs/1801.05030)

##### PDF
[http://arxiv.org/pdf/1801.05030](http://arxiv.org/pdf/1801.05030)

