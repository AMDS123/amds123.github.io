---
layout: post
title: "RECAL: Reuse of Established CNN classifer Apropos unsupervised Learning paradigm"
date: 2019-06-15 06:46:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Face Embedding CNN Classification Gradient_Descent
author: Jayasree Saha, Jayanta Mukhopadhyay
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, clustering with deep network framework has attracted attention of several researchers in the computer vision community. Deep framework gains extensive attention due to its efficiency and scalability towards large-scale and high-dimensional data. In this paper, we transform supervised CNN classifier architecture into an unsupervised clustering model, called RECAL, which jointly learns discriminative embedding subspace and cluster labels. RECAL is made up of feature extraction layers which are convolutional, followed by unsupervised classifier layers which is fully connected. A multinomial logistic regression function (softmax) stacked on top of classifier layers. We train this network using stochastic gradient descent (SGD) optimizer. However, the successful implementation of our model is revolved around the design of loss function. Our loss function uses the heuristics that true partitioning entails lower entropy given that the class distribution is not heavily skewed. This is a trade-off between the situations of "skewed distribution" and "low-entropy". To handle this, we have proposed classification entropy and class entropy which are the two components of our loss function. In this approach, size of the mini-batch should be kept high. Experimental results indicate the consistent and competitive behavior of our model for clustering well-known digit, multi-viewed object and face datasets. Morever, we use this model to generate unsupervised patch segmentation for multi-spectral LISS-IV images. We observe that it is able to distinguish built-up area, wet land, vegetation and waterbody from the underlying scene.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06480](http://arxiv.org/abs/1906.06480)

##### PDF
[http://arxiv.org/pdf/1906.06480](http://arxiv.org/pdf/1906.06480)

