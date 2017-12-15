---
layout: post
title: "Universal Correspondence Network"
date: 2016-10-31 06:32:03
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Christopher B. Choy, JunYoung Gwak, Silvio Savarese, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
We present a deep learning framework for accurate visual correspondences and demonstrate its effectiveness for both geometric and semantic matching, spanning across rigid motions to intra-class shape or appearance variations. In contrast to previous CNN-based approaches that optimize a surrogate patch similarity objective, we use deep metric learning to directly learn a feature space that preserves either geometric or semantic similarity. Our fully convolutional architecture, along with a novel correspondence contrastive loss allows faster training by effective reuse of computations, accurate gradient computation through the use of thousands of examples per image pair and faster testing with $O(n)$ feed forward passes for $n$ keypoints, instead of $O(n^2)$ for typical patch similarity methods. We propose a convolutional spatial transformer to mimic patch normalization in traditional features like SIFT, which is shown to dramatically boost accuracy for semantic correspondences across intra-class shape variations. Extensive experiments on KITTI, PASCAL, and CUB-2011 datasets demonstrate the significant advantages of our features over prior works that use either hand-constructed or learned features.

##### Abstract (translated by Google)
我们提出了一个精确的视觉对应的深度学习框架，并展示其对几何和语义匹配的有效性，横跨刚性运动到类内形状或外观变化。与以前基于CNN的优化替代补丁相似性目标的方法相反，我们使用深度度量学习来直接学习保留几何或语义相似性的特征空间。我们的完全卷积体系结构，以及一个新的通信对比损失，允许通过有效地重复使用计算来更快地进行训练，通过使用每个图像对的数千个示例进行准确的梯度计算，并且使用$ O（n）$前馈通过$ n $关键点，而不是$ O（n ^ 2）$典型的补丁相似性方法。我们提出了一种卷积空间转换器来模拟像SIFT这样的传统特征中的补丁归一化，其被显示显着提高跨类内形状变化的语义对应的准确性。 KITTI，PASCAL和CUB-2011数据集的大量实验证明了我们的特征比使用手工构造或学习特征的先前作品的显着优点。

##### URL
[https://arxiv.org/abs/1606.03558](https://arxiv.org/abs/1606.03558)

##### PDF
[https://arxiv.org/pdf/1606.03558](https://arxiv.org/pdf/1606.03558)

