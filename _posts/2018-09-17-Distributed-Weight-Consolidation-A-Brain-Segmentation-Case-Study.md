---
layout: post
title: "Distributed Weight Consolidation: A Brain Segmentation Case Study"
date: 2018-09-17 18:03:02
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Patrick McClure, Charles Y. Zheng, Jakub R. Kaczmarzyk, John Rogers-Lee, Satrajit S. Ghosh, Dylan Nielson, Peter Bandettini, Francisco Pereira
mathjax: true
---

* content
{:toc}

##### Abstract
Collecting the large datasets needed to train deep neural networks can be very difficult, particularly for the many applications for which sharing and pooling data is complicated by practical, ethical, or legal concerns. However, it may be the case that derivative datasets or predictive models developed within individual sites can be shared and combined with fewer restrictions. Training on distributed data and combining the resulting networks is often viewed as continual learning, but these methods require networks to be trained sequentially. In this paper, we introduce distributed weight consolidation (DWC), a continual learning method to consolidate the weights of separate neural networks, each trained on an independent dataset. We evaluated DWC with a brain segmentation case study, where we consolidated dilated convolutional neural networks trained on independent structural magnetic resonance imaging (sMRI) datasets from different sites. We found that DWC led to increased performance on held-out test sets from the different sites, as well as on a very large and completely independent multi-site dataset. Moreover, performance was close to that obtained by training a single network on data from all sites.

##### Abstract (translated by Google)
收集训练深度神经网络所需的大型数据集可能非常困难，特别是对于因实际，道德或法律问题而使共享和汇集数据复杂化的许多应用程序。然而，可能的情况是，可以共享在各个站点内开发的衍生数据集或预测模型，并将其与较少的限制相结合。对分布式数据进行培训并将所得到的网络组合在一起通常被视为持续学习，但这些方法需要对网络进行顺序培训。在本文中，我们介绍了分布式权重合并（DWC），这是一种连续学习方法，用于巩固单独神经网络的权重，每个神经网络都在一个独立的数据集上进行训练。我们通过脑分割案例研究评估了DWC，其中我们合并了来自不同站点的独立结构磁共振成像（sMRI）数据集训练的扩张卷积神经网络。我们发现DWC可以提高不同站点的保持测试集的性能，以及非常大且完全独立的多站点数据集。此外，性能接近于通过对所有站点的数据进行单一网络培训所获得的性能。

##### URL
[http://arxiv.org/abs/1805.10863](http://arxiv.org/abs/1805.10863)

##### PDF
[http://arxiv.org/pdf/1805.10863](http://arxiv.org/pdf/1805.10863)

