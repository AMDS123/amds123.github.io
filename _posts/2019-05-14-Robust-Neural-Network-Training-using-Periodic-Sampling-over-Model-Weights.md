---
layout: post
title: "Robust Neural Network Training using Periodic Sampling over Model Weights"
date: 2019-05-14 18:00:23
categories: arXiv_AI
tags: arXiv_AI Segmentation Face Classification Detection
author: Samarth Tripathi, Jiayi Liu, Unmesh Kurup, Mohak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks provide best-in-class performance for a number of computer vision problems. However, training these networks is computationally intensive and requires fine-tuning various hyperparameters. In addition, performance swings widely as the network converges making it hard to decide when to stop training. In this paper, we introduce a trio of techniques (PSWA, PWALKS, and PSWM) centered around periodic sampling of model weights that provide consistent and more robust convergence on a variety of vision problems (classification, detection, segmentation) and gradient update methods (vanilla SGD, Momentum, Adam) with marginal additional computation time. Our techniques use existing optimal training policies but converge in a less volatile fashion with performance improvements that are approximately monotonic. Our analysis of the loss surface shows that these techniques also produce minima that are deeper and wider than those found by SGD.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.05774](http://arxiv.org/abs/1905.05774)

##### PDF
[http://arxiv.org/pdf/1905.05774](http://arxiv.org/pdf/1905.05774)

