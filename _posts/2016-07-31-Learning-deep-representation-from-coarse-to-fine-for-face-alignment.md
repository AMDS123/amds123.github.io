---
layout: post
title: "Learning deep representation from coarse to fine for face alignment"
date: 2016-07-31 11:02:40
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Zhiwen Shao, Shouhong Ding, Yiru Zhao, Qinchuan Zhang, Lizhuang Ma
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel face alignment method that trains deep convolutional network from coarse to fine. It divides given landmarks into principal subset and elaborate subset. We firstly keep a large weight for principal subset to make our network primarily predict their locations while slightly take elaborate subset into account. Next the weight of principal subset is gradually decreased until two subsets have equivalent weights. This process contributes to learn a good initial model and search the optimal model smoothly to avoid missing fairly good intermediate models in subsequent procedures. On the challenging COFW dataset [1], our method achieves 6.33% mean error with a reduction of 21.37% compared with the best previous result [2].

##### Abstract (translated by Google)
在本文中，我们提出了一种新的面对齐方法，将深度卷积网络从粗到精。它将给定的地标划分为主子集和精细子集。我们首先保留主子集的一个很大的权重，使我们的网络主要预测他们的位置，同时稍微考虑一个详细的子集。接下来，主子集的权重逐渐减少，直到两个子集具有相等的权重。这个过程有助于学习一个好的初始模型，并顺利地搜索最优模型，以避免在后续程序中丢失相当好的中间模型。在具有挑战性的COFW数据集[1]中，我们的方法达到了6.33％的平均误差，比最好的结果减少了21.37％[2]。

##### URL
[https://arxiv.org/abs/1608.00207](https://arxiv.org/abs/1608.00207)

##### PDF
[https://arxiv.org/pdf/1608.00207](https://arxiv.org/pdf/1608.00207)

