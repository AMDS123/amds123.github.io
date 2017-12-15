---
layout: post
title: "Deep Learning Markov Random Field for Semantic Segmentation"
date: 2017-08-08 09:24:18
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference Deep_Learning Relation
author: Ziwei Liu, Xiaoxiao Li, Ping Luo, Chen Change Loy, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation tasks can be well modeled by Markov Random Field (MRF). This paper addresses semantic segmentation by incorporating high-order relations and mixture of label contexts into MRF. Unlike previous works that optimized MRFs using iterative algorithm, we solve MRF by proposing a Convolutional Neural Network (CNN), namely Deep Parsing Network (DPN), which enables deterministic end-to-end computation in a single forward pass. Specifically, DPN extends a contemporary CNN to model unary terms and additional layers are devised to approximate the mean field (MF) algorithm for pairwise terms. It has several appealing properties. First, different from the recent works that required many iterations of MF during back-propagation, DPN is able to achieve high performance by approximating one iteration of MF. Second, DPN represents various types of pairwise terms, making many existing models as its special cases. Furthermore, pairwise terms in DPN provide a unified framework to encode rich contextual information in high-dimensional data, such as images and videos. Third, DPN makes MF easier to be parallelized and speeded up, thus enabling efficient inference. DPN is thoroughly evaluated on standard semantic image/video segmentation benchmarks, where a single DPN model yields state-of-the-art segmentation accuracies on PASCAL VOC 2012, Cityscapes dataset and CamVid dataset.

##### Abstract (translated by Google)
语义分割任务可以很好地由马尔可夫随机场（MRF）建模。本文通过将高阶关系和标签上下文混合到MRF中来解决语义分割问题。与以前使用迭代算法优化MRF的工作不同，我们通过提出卷积神经网络（CNN）即深度解析网络（DPN）来解决MRF问题，该算法能够在单个正向通道中进行确定性的端到端计算。具体而言，DPN将现代CNN扩展为对一元项进行建模，并设计附加层来近似平均场（MF）算法的成对项。它有几个吸引人的属性。首先，与最近需要在反向传播过程中进行多次迭代的工作不同，DPN能够通过接近MF的一次迭代来实现高性能。其次，DPN代表了各种各样的配对术语，使许多现有的模型成为其特例。此外，DPN中的成对词汇提供了一个统一的框架，用于在高维数据（如图像和视频）中编码丰富的上下文信息。第三，DPN使得MF更容易并行和加速，从而能够进行有效的推断。 DPN在标准语义图像/视频分割基准上进行了全面评估，其中单个DPN模型在PASCAL VOC 2012，Cityscapes数据集和CamVid数据集上获得了最先进的分割精度。

##### URL
[https://arxiv.org/abs/1606.07230](https://arxiv.org/abs/1606.07230)

##### PDF
[https://arxiv.org/pdf/1606.07230](https://arxiv.org/pdf/1606.07230)

