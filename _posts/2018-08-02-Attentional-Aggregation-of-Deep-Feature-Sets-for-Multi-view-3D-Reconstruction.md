---
layout: post
title: "Attentional Aggregation of Deep Feature Sets for Multi-view 3D Reconstruction"
date: 2018-08-02 11:09:13
categories: arXiv_AI
tags: arXiv_AI Attention
author: Bo Yang, Sen Wang, Andrew Markham, Niki Trigoni
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of recovering an underlying 3D shape from a set of images. Existing learning based approaches usually resort to recurrent neural nets, e.g., GRU, or intuitive pooling operations, e.g., max/mean pooling, to fuse multiple deep features encoded from input images. However, GRU based approaches are unable to consistently estimate 3D shapes given the same set of input images as the recurrent unit is permutation variant. It is also unlikely to refine the 3D shape given more images due to the long-term memory loss of GRU. The widely used pooling approaches are limited to capturing only the first order/moment information, ignoring other valuable features. In this paper, we present a new feed-forward neural module, named AttSets, together with a dedicated training algorithm, named JTSO, to attentionally aggregate an arbitrary sized deep feature set for multi-view 3D reconstruction. AttSets is permutation invariant, computationally efficient, flexible and robust to multiple input images. We thoroughly evaluate various properties of AttSets on large public datasets. Extensive experiments show AttSets together with JTSO algorithm significantly outperforms existing aggregation approaches.

##### Abstract (translated by Google)
我们研究了从一组图像中恢复底层3D形状的问题。现有的基于学习的方法通常采用递归神经网络（例如GRU）或直观池化操作（例如，最大/平均合并）来融合从输入图像编码的多个深度特征。然而，基于GRU的方法不能一致地估计给定相同输入图像集的3D形状，因为循环单元是置换变体。由于GRU的长期记忆丧失，给定更多图像也不太可能改善3D形状。广泛使用的池化方法仅限于捕获第一个订单/时刻信息，忽略其他有价值的特征。在本文中，我们提出了一个新的前馈神经模块，名为AttSets，以及一个名为JTSO的专用训练算法，用于注意聚合任意大小的深度特征集，用于多视图3D重建。 AttSets是排列不变的，计算效率高，灵活且对多个输入图像稳健。我们在大型公共数据集上彻底评估了AttSets的各种属性。大量实验表明，AttSets和JTSO算法明显优于现有的聚合方法。

##### URL
[http://arxiv.org/abs/1808.00758](http://arxiv.org/abs/1808.00758)

##### PDF
[http://arxiv.org/pdf/1808.00758](http://arxiv.org/pdf/1808.00758)

