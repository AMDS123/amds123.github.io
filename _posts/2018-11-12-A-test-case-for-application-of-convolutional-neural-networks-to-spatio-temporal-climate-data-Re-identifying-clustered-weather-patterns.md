---
layout: post
title: "A test case for application of convolutional neural networks to spatio-temporal climate data: Re-identifying clustered weather patterns"
date: 2018-11-12 15:56:30
categories: arXiv_CV
tags: arXiv_CV CNN
author: Ashesh Chattopadhyay, Pedram Hassanzadeh, Saba Pasha
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) can potentially provide powerful tools for classifying and identifying patterns in climate and environmental data. However, because of the inherent complexities of such data, which are often spatio-temporal, chaotic, and non-stationary, the CNN algorithms must be designed/evaluated for each specific dataset and application. Yet to start, CNN, a supervised technique, requires a large labeled dataset. Labeling demands (human) expert time, which combined with the limited number of relevant examples in this area, can discourage using CNNs for new problems. To address these challenges, here we (1) Propose an effective auto-labeling strategy based on using an unsupervised clustering algorithm and evaluating the performance of CNNs in re-identifying these clusters; (2) Use this approach to label thousands of daily large-scale weather patterns over North America in the outputs of a fully-coupled climate model and show the capabilities of CNNs in re-identifying the 4 clustered regimes. The deep CNN trained with $1000$ samples or more per cluster has an accuracy of $90\%$ or better. Accuracy scales monotonically but nonlinearly with the size of the training set, e.g. reaching $94\%$ with $3000$ training samples per cluster. Effects of architecture and hyperparameters on the performance of CNNs are examined and discussed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04817](http://arxiv.org/abs/1811.04817)

##### PDF
[http://arxiv.org/pdf/1811.04817](http://arxiv.org/pdf/1811.04817)

