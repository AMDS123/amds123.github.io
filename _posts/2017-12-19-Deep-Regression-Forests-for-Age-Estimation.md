---
layout: post
title: "Deep Regression Forests for Age Estimation"
date: 2017-12-19 20:42:15
categories: arXiv_CV
tags: arXiv_CV CNN
author: Wei Shen, Yilu Guo, Yan Wang, Kai Zhao, Bo Wang, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Age estimation from facial images is typically cast as a nonlinear regression problem. The main challenge of this problem is the facial feature space w.r.t. ages is heterogeneous, due to the large variation in facial appearance across different persons of the same age and the non-stationary property of aging patterns. In this paper, we propose Deep Regression Forests (DRFs), an end-to-end model, for age estimation. DRFs connect the split nodes to a fully connected layer of a convolutional neural network (CNN) and deal with heterogeneous data by jointly learning input-dependant data partitions at the split nodes and data abstractions at the leaf nodes. This joint learning follows an alternating strategy: First, by fixing the leaf nodes, the split nodes as well as the CNN parameters are optimized by Back-propagation; Then, by fixing the split nodes, the leaf nodes are optimized by iterating a step-size free and fast-converging update rule derived from Variational Bounding. We verify the proposed DRFs on three standard age estimation benchmarks and achieve state-of-the-art results on all of them.

##### Abstract (translated by Google)
来自面部图像的年龄估计通常被视为非线性回归问题。这个问题的主要挑战是面部特征空间w.r.t.年龄是不均匀的，这是由于同一年龄段不同人的面部外观变化很大，以及衰老模式的非平稳性。在本文中，我们提出深度回归森林（DRFs），一种端到端模型，用于年龄估计。 DRF将分离节点连接到卷积神经网络（CNN）的完全连接层，并通过联合学习分裂节点处的输入相关数据分区和叶节点处的数据抽象来处理异构数据。这种联合学习遵循交替策略：首先，通过修复叶节点，分裂节点以及CNN参数通过反向传播进行优化;然后，通过修复分裂节点，通过迭代从变分边界导出的步长自由和快速收敛的更新规则来优化叶节点。我们在三个标准年龄估算基准上验证了提议的DRF，并在所有这些基准上取得了最新的成果。

##### URL
[https://arxiv.org/abs/1712.07195](https://arxiv.org/abs/1712.07195)

##### PDF
[https://arxiv.org/pdf/1712.07195](https://arxiv.org/pdf/1712.07195)

