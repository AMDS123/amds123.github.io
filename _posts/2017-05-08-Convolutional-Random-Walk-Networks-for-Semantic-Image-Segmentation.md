---
layout: post
title: "Convolutional Random Walk Networks for Semantic Image Segmentation"
date: 2017-05-08 17:49:21
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Prediction Relation
author: Gedas Bertasius, Lorenzo Torresani, Stella X. Yu, Jianbo Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Most current semantic segmentation methods rely on fully convolutional networks (FCNs). However, their use of large receptive fields and many pooling layers cause low spatial resolution inside the deep layers. This leads to predictions with poor localization around the boundaries. Prior work has attempted to address this issue by post-processing predictions with CRFs or MRFs. But such models often fail to capture semantic relationships between objects, which causes spatially disjoint predictions. To overcome these problems, recent methods integrated CRFs or MRFs into an FCN framework. The downside of these new models is that they have much higher complexity than traditional FCNs, which renders training and testing more challenging. In this work we introduce a simple, yet effective Convolutional Random Walk Network (RWN) that addresses the issues of poor boundary localization and spatially fragmented predictions with very little increase in model complexity. Our proposed RWN jointly optimizes the objectives of pixelwise affinity and semantic segmentation. It combines these two objectives via a novel random walk layer that enforces consistent spatial grouping in the deep layers of the network. Our RWN is implemented using standard convolution and matrix multiplication. This allows an easy integration into existing FCN frameworks and it enables end-to-end training of the whole network via standard back-propagation. Our implementation of RWN requires just $131$ additional parameters compared to the traditional FCNs, and yet it consistently produces an improvement over the FCNs on semantic segmentation and scene labeling.

##### Abstract (translated by Google)
大多数当前的语义分割方法依赖于完全卷积网络（FCN）。然而，它们使用大的感受野和许多汇合层导致深层内的低空间分辨率。这导致预测与边界周围的本地化不佳。之前的工作试图通过CRF或MRF的后处理预测来解决这个问题。但是这样的模型通常不能捕捉到对象之间的语义关系，这导致空间上不相关的预测。为了克服这些问题，最近的方法将CRF或MRF集成到FCN框架中。这些新模型的缺点是它们比传统的FCN复杂得多，这使得训练和测试更具挑战性。在这项工作中，我们介绍一个简单而有效的卷积随机游走网络（RWN），它解决了边界定位不良和空间碎片化预测的问题，而模型复杂性却几乎没有增加。我们提出的RWN联合优化了像素亲和性和语义分割的目标。它通过一个新的随机游走层将这两个目标结合起来，在网络的深层实施一致的空间分组。我们的RWN是使用标准卷积和矩阵乘法实现的。这样可以轻松整合到现有的FCN框架中，并通过标准的反向传播实现整个网络的端到端培训。与传统的FCN相比，我们的RWN实现需要额外的131美元的额外参数，但是它在语义分割和场景标记方面始终如一地改进FCN。

##### URL
[https://arxiv.org/abs/1605.07681](https://arxiv.org/abs/1605.07681)

##### PDF
[https://arxiv.org/pdf/1605.07681](https://arxiv.org/pdf/1605.07681)

