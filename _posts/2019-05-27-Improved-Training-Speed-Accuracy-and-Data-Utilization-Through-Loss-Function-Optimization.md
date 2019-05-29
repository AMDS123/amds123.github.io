---
layout: post
title: "Improved Training Speed, Accuracy, and Data Utilization Through Loss Function Optimization"
date: 2019-05-27 22:24:21
categories: arXiv_CV
tags: arXiv_CV Image_Classification Optimization Classification
author: Santiago Gonzalez, Risto Miikkulainen
mathjax: true
---

* content
{:toc}

##### Abstract
As the complexity of neural network models has grown, it has become increasingly important to optimize their design automatically through metalearning. Methods for discovering hyperparameters, topologies, and learning rate schedules have lead to significant increases in performance. This paper shows that loss functions can be optimized with metalearning as well, and result in similar improvements. The method, Genetic Loss-function Optimization (GLO), discovers loss functions de novo, and optimizes them for a target task. Leveraging techniques from genetic programming, GLO builds loss functions hierarchically from a set of operators and leaf nodes. These functions are repeatedly recombined and mutated to find an optimal structure, and then a covariance-matrix adaptation evolutionary strategy (CMA-ES) is used to find optimal coefficients. Networks trained with GLO loss functions are found to outperform the standard cross-entropy loss on standard image classification tasks. Training with these new loss functions requires fewer steps, results in lower test error, and allows for smaller datasets to be used. Loss-function optimization thus provides a new dimension of metalearning, and constitutes an important step towards AutoML.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11528](https://arxiv.org/abs/1905.11528)

##### PDF
[https://arxiv.org/pdf/1905.11528](https://arxiv.org/pdf/1905.11528)

