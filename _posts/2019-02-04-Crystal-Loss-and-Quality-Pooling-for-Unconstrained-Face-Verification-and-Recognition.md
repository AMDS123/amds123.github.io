---
layout: post
title: "Crystal Loss and Quality Pooling for Unconstrained Face Verification and Recognition"
date: 2019-02-04 03:13:42
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification Deep_Learning Recognition
author: Rajeev Ranjan, Ankan Bansal, Hongyu Xu, Swami Sankaranarayanan, Jun-Cheng Chen, Carlos D. Castillo, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, the performance of face verification and recognition systems based on deep convolutional neural networks (DCNNs) has significantly improved. A typical pipeline for face verification includes training a deep network for subject classification with softmax loss, using the penultimate layer output as the feature descriptor, and generating a cosine similarity score given a pair of face images or videos. The softmax loss function does not optimize the features to have higher similarity score for positive pairs and lower similarity score for negative pairs, which leads to a performance gap. In this paper, we propose a new loss function, called Crystal Loss, that restricts the features to lie on a hypersphere of a fixed radius. The loss can be easily implemented using existing deep learning frameworks. We show that integrating this simple step in the training pipeline significantly improves the performance of face verification and recognition systems. We achieve state-of-the-art performance for face verification and recognition on challenging LFW, IJB-A, IJB-B and IJB-C datasets over a large range of false alarm rates (10-1 to 10-7).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.01159](http://arxiv.org/abs/1804.01159)

##### PDF
[http://arxiv.org/pdf/1804.01159](http://arxiv.org/pdf/1804.01159)

