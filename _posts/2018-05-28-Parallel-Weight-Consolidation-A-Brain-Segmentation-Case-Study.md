---
layout: post
title: "Parallel Weight Consolidation: A Brain Segmentation Case Study"
date: 2018-05-28 10:50:11
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN
author: Patrick McClure, Charles Zheng, Francisco Pereira, Jakub Kaczmarzyk, John Rogers-Lee, Dylan Nielson, Peter Bandettini
mathjax: true
---

* content
{:toc}

##### Abstract
Collecting the large datasets needed to train deep neural networks can be very difficult, particularly for the many applications for which sharing and pooling data is complicated by practical, ethical, or legal concerns. However, it may be the case that derivative datasets or predictive models developed within individual sites can be shared and combined with fewer restrictions. Training on distributed datasets and combining the resulting networks is often viewed as continual learning, but these methods require networks to be trained sequentially. In this paper, we introduce parallel weight consolidation (PWC), a continual learning method to consolidate the weights of neural networks trained in parallel on independent datasets. We perform a brain segmentation case study using PWC to consolidate several dilated convolutional neural networks trained in parallel on independent structural magnetic resonance imaging (sMRI) datasets from different sites. We found that PWC led to increased performance on held-out test sets from the different sites, as well as on a very large and completely independent multi-site dataset. This demonstrates the feasibility of PWC for combining the knowledge learned by networks trained on different datasets.

##### Abstract (translated by Google)
收集训练深度神经网络所需的大型数据集可能非常困难，特别是对于实际，道德或法律方面的问题而言，共享和共享数据的许多应用程序都很复杂。但是，可能会出现这样的情况：在各个站点内开发的衍生数据集或预测模型可以共享并与更少的限制结合使用。对分布式数据集进行培训并将所得到的网络进行组合通常被视为持续学习，但这些方法需要对网络进行顺序培训。在本文中，我们引入平行权重合并（PWC），这是一种连续学习方法，用于合并在独立数据集上并行训练的神经网络的权重。我们使用PWC进行脑分割案例研究，以巩固在来自不同地点的独立结构磁共振成像（sMRI）数据集上平行训练的几个扩张卷积神经网络。我们发现PWC导致不同站点的外挂测试集以及非常大且完全独立的多站点数据集上的性能提高。这证明了PWC结合在不同数据集上训练的网络学到的知识的可行性。

##### URL
[http://arxiv.org/abs/1805.10863](http://arxiv.org/abs/1805.10863)

##### PDF
[http://arxiv.org/pdf/1805.10863](http://arxiv.org/pdf/1805.10863)

