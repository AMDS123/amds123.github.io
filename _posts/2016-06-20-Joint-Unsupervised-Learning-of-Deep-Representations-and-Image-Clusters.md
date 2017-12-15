---
layout: post
title: "Joint Unsupervised Learning of Deep Representations and Image Clusters"
date: 2016-06-20 19:56:16
categories: arXiv_CV
tags: arXiv_CV CNN Represenation_Learning
author: Jianwei Yang, Devi Parikh, Dhruv Batra
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a recurrent framework for Joint Unsupervised LEarning (JULE) of deep representations and image clusters. In our framework, successive operations in a clustering algorithm are expressed as steps in a recurrent process, stacked on top of representations output by a Convolutional Neural Network (CNN). During training, image clusters and representations are updated jointly: image clustering is conducted in the forward pass, while representation learning in the backward pass. Our key idea behind this framework is that good representations are beneficial to image clustering and clustering results provide supervisory signals to representation learning. By integrating two processes into a single model with a unified weighted triplet loss and optimizing it end-to-end, we can obtain not only more powerful representations, but also more precise image clusters. Extensive experiments show that our method outperforms the state-of-the-art on image clustering across a variety of image datasets. Moreover, the learned representations generalize well when transferred to other tasks.

##### Abstract (translated by Google)
在本文中，我们提出了一个关于深度表示和图像集群的联合无监督学习（JULE）的循环框架。在我们的框架中，聚类算法中的连续操作表示为循环过程中的步骤，堆叠在由卷积神经网络（CNN）输出的表示之上。在训练过程中，图像的聚类和表示是共同更新的：图像聚类是在正向过程中进行的，而表示学习是在向后的过程中进行的。这个框架背后的关键思想是好的表示有利于图像聚类，聚类结果为表示学习提供监督信号。通过将两个过程整合到统一加权三重损失的单个模型中，并将其优化到端到端，不仅可以获得更强大的表示，还可以获得更精确的图像聚类。大量的实验表明，我们的方法胜过了在各种图像数据集上进行图像聚类的最新技术。而且，学到的表示在转移到其他任务时总结得很好。

##### URL
[https://arxiv.org/abs/1604.03628](https://arxiv.org/abs/1604.03628)

##### PDF
[https://arxiv.org/pdf/1604.03628](https://arxiv.org/pdf/1604.03628)

