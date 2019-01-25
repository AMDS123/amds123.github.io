---
layout: post
title: "Similarity Learning for High-Dimensional Sparse Data"
date: 2015-10-21 13:45:00
categories: arXiv_AI
tags: arXiv_AI Sparse Classification
author: Kuan Liu, Aur&#xe9;lien Bellet, Fei Sha
mathjax: true
---

* content
{:toc}

##### Abstract
A good measure of similarity between data points is crucial to many tasks in machine learning. Similarity and metric learning methods learn such measures automatically from data, but they do not scale well respect to the dimensionality of the data. In this paper, we propose a method that can learn efficiently similarity measure from high-dimensional sparse data. The core idea is to parameterize the similarity measure as a convex combination of rank-one matrices with specific sparsity structures. The parameters are then optimized with an approximate Frank-Wolfe procedure to maximally satisfy relative similarity constraints on the training data. Our algorithm greedily incorporates one pair of features at a time into the similarity measure, providing an efficient way to control the number of active features and thus reduce overfitting. It enjoys very appealing convergence guarantees and its time and memory complexity depends on the sparsity of the data instead of the dimension of the feature space. Our experiments on real-world high-dimensional datasets demonstrate its potential for classification, dimensionality reduction and data exploration.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1411.2374](http://arxiv.org/abs/1411.2374)

##### PDF
[http://arxiv.org/pdf/1411.2374](http://arxiv.org/pdf/1411.2374)

