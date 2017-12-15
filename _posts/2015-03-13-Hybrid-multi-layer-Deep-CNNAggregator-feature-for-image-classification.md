---
layout: post
title: "Hybrid multi-layer Deep CNN/Aggregator feature for image classification"
date: 2015-03-13 13:49:26
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Praveen Kulkarni, Joaquin Zepeda, Frederic Jurie, Patrick Perez, Louis Chevallier
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolutional Neural Networks (DCNN) have established a remarkable performance benchmark in the field of image classification, displacing classical approaches based on hand-tailored aggregations of local descriptors. Yet DCNNs impose high computational burdens both at training and at testing time, and training them requires collecting and annotating large amounts of training data. Supervised adaptation methods have been proposed in the literature that partially re-learn a transferred DCNN structure from a new target dataset. Yet these require expensive bounding-box annotations and are still computationally expensive to learn. In this paper, we address these shortcomings of DCNN adaptation schemes by proposing a hybrid approach that combines conventional, unsupervised aggregators such as Bag-of-Words (BoW), with the DCNN pipeline by treating the output of intermediate layers as densely extracted local descriptors. We test a variant of our approach that uses only intermediate DCNN layers on the standard PASCAL VOC 2007 dataset and show performance significantly higher than the standard BoW model and comparable to Fisher vector aggregation but with a feature that is 150 times smaller. A second variant of our approach that includes the fully connected DCNN layers significantly outperforms Fisher vector schemes and performs comparably to DCNN approaches adapted to Pascal VOC 2007, yet at only a small fraction of the training and testing cost.

##### Abstract (translated by Google)
深度卷积神经网络（DCNN）在图像分类领域建立了卓越的性能基准，取代了基于手工量化的局部描述符聚合的经典方法。然而，DCNN在训练和测试时都会给计算带来很大的负担，而训练它们需要收集和注释大量的训练数据。已经在文献中提出了监督的适应方法，其从新的目标数据集中部分地重新学习转移的DCNN结构。然而，这些需要昂贵的边框注释，并且仍然在计算上花费昂贵。在本文中，我们通过提出一种混合方法来解决DCNN自适应方案的这些缺点，即将传统的非监督聚合器（如袋子）与DCNN管线相结合，将中间层的输出视为密集提取的局部描述符。我们测试了我们的方法的一种变体，其在标准PASCAL VOC 2007数据集上仅使用中间DCNN层，并显示比标准BoW模型显着更高的性能，并且与费希尔矢量聚合相当，但具有小150倍的特征。我们的方法的第二个变体包括完全连接的DCNN层明显优于Fisher矢量方案，并且与适用于Pascal VOC 2007的DCNN方法相当，但仅占培训和测试成本的一小部分。

##### URL
[https://arxiv.org/abs/1503.04065](https://arxiv.org/abs/1503.04065)

##### PDF
[https://arxiv.org/pdf/1503.04065](https://arxiv.org/pdf/1503.04065)

