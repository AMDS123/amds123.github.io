---
layout: post
title: "Learning Neural Models for End-to-End Clustering"
date: 2018-07-11 08:45:45
categories: arXiv_AI
tags: arXiv_AI
author: Benjamin Bruno Meier, Ismail Elezi, Mohammadreza Amirian, Oliver Durr, Thilo Stadelmann
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel end-to-end neural network architecture that, once trained, directly outputs a probabilistic clustering of a batch of input examples in one pass. It estimates a distribution over the number of clusters $k$, and for each $1 \leq k \leq k_\mathrm{max}$, a distribution over the individual cluster assignment for each data point. The network is trained in advance in a supervised fashion on separate data to learn grouping by any perceptual similarity criterion based on pairwise labels (same/different group). It can then be applied to different data containing different groups. We demonstrate promising performance on high-dimensional data like images (COIL-100) and speech (TIMIT). We call this ``learning to cluster'' and show its conceptual difference to deep metric learning, semi-supervise clustering and other related approaches while having the advantage of performing learnable clustering fully end-to-end.

##### Abstract (translated by Google)
我们提出了一种新颖的端到端神经网络架构，一旦经过训练，就可以一次性直接输出一批输入示例的概率聚类。它估计了聚类数量$ k $以及每个$ 1 \ leq k \ leq k_ \ mathrm {max} $的分布，这是每个数据点的单个聚类分配的分布。预先以监督的方式对网络进行单独数据训练，以通过基于成对标签（相同/不同组）的任何感知相似性标准来学习分组。然后，它可以应用于包含不同组的不同数据。我们在高维数据（如图像（COIL-100）和语音（TIMIT））上展示了出色的性能。我们称之为“学习集群”，并将其概念差异显示为深度度量学习，半监督聚类和其他相关方法，同时具有完全端到端执行可学习聚类的优势。

##### URL
[http://arxiv.org/abs/1807.04001](http://arxiv.org/abs/1807.04001)

##### PDF
[http://arxiv.org/pdf/1807.04001](http://arxiv.org/pdf/1807.04001)

