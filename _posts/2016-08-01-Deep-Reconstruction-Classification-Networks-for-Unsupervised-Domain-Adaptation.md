---
layout: post
title: "Deep Reconstruction-Classification Networks for Unsupervised Domain Adaptation"
date: 2016-08-01 09:58:13
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning Recognition
author: Muhammad Ghifary, W. Bastiaan Kleijn, Mengjie Zhang, David Balduzzi, Wen Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel unsupervised domain adaptation algorithm based on deep learning for visual object recognition. Specifically, we design a new model called Deep Reconstruction-Classification Network (DRCN), which jointly learns a shared encoding representation for two tasks: i) supervised classification of labeled source data, and ii) unsupervised reconstruction of unlabeled target data.In this way, the learnt representation not only preserves discriminability, but also encodes useful information from the target domain. Our new DRCN model can be optimized by using backpropagation similarly as the standard neural networks. We evaluate the performance of DRCN on a series of cross-domain object recognition tasks, where DRCN provides a considerable improvement (up to ~8% in accuracy) over the prior state-of-the-art algorithms. Interestingly, we also observe that the reconstruction pipeline of DRCN transforms images from the source domain into images whose appearance resembles the target dataset. This suggests that DRCN's performance is due to constructing a single composite representation that encodes information about both the structure of target images and the classification of source images. Finally, we provide a formal analysis to justify the algorithm's objective in domain adaptation context.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于深度学习的视觉目标识别的无监督域自适应算法。具体而言，我们设计了一个名为深度重建分类网络（Deep Reconstruction-Classification Network，DRCN）的新模型，它共同学习了两个任务的共享编码表示：i）有标记的源数据的监督分类; ii）无标记的目标数据的重建。学习表示不仅保留了可区分性，而且还编码了来自目标域的有用信息。我们的新的DRCN模型可以通过与标准神经网络类似的反向传播来优化。我们评估了DRCN在一系列跨领域对象识别任务上的性能，其中DRCN比先前的最先进的算法提供了相当大的改进（高达〜8％的准确度）。有趣的是，我们还观察到，DRCN的重建流水线将图像从源域转换成外观与目标数据集相似的图像。这表明，DRCN的性能是由于构建了一个单一的复合表示，对目标图像的结构和源图像的分类进行编码。最后，我们提供了一个正式的分析来证明算法在领域适应环境下的目标。

##### URL
[https://arxiv.org/abs/1607.03516](https://arxiv.org/abs/1607.03516)

##### PDF
[https://arxiv.org/pdf/1607.03516](https://arxiv.org/pdf/1607.03516)

