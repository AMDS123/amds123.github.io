---
layout: post
title: "Network Compression using Correlation Analysis of Layer Responses"
date: 2018-11-16 21:33:41
categories: arXiv_CV
tags: arXiv_CV Relation
author: Xavier Suau, Luca Zappella, Nicholas Apostoloff
mathjax: true
---

* content
{:toc}

##### Abstract
Principal Filter Analysis (PFA) is an easy to implement, yet effective method for neural network compression. PFA exploits the intrinsic correlation between filter responses within network layers to recommend a smaller network footprint. We propose two compression algorithms: the first allows a user to specify the proportion of the original spectral energy that should be preserved in each layer after compression, while the second is a heuristic that leads to a parameter-free approach that automatically selects the compression used at each layer. Both algorithms are evaluated against several architectures and datasets, and we show considerable compression rates without compromising accuracy, e.g., for VGG-16 on CIFAR-10, CIFAR-100 and ImageNet, PFA achieves a compression rate of 8x, 3x, and 1.4x with an accuracy gain of 0.4%, 1.4% points, and 2.4% respectively. In our tests we also demonstrate that networks compressed with PFA achieve an accuracy that is very close to the empirical upper bound for a given compression ratio. Finally, we show how PFA is an effective tool for simultaneous compression and domain adaptation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.10585](http://arxiv.org/abs/1807.10585)

##### PDF
[http://arxiv.org/pdf/1807.10585](http://arxiv.org/pdf/1807.10585)

