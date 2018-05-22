---
layout: post
title: "CapProNet: Deep Feature Learning via Orthogonal Projections onto Capsule Subspaces"
date: 2018-05-19 16:50:37
categories: arXiv_CV
tags: arXiv_CV
author: Liheng Zhang, Marzieh Edraki, Guo-Jun Qi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we formalize the idea behind capsule nets of using a capsule vector rather than a neuron activation to predict the label of samples. To this end, we propose to learn a group of capsule subspaces onto which an input feature vector is projected. Then the lengths of resultant capsules are used to score the probability of belonging to different classes. We train such a Capsule Projection Network (CapProNet) by learning an orthogonal projection matrix for each capsule subspace, and show that each capsule subspace is updated until it contains input feature vectors corresponding to the associated class. Only a small negligible computing overhead is incurred to train the network in low-dimensional capsule subspaces or through an alternative hyper-power iteration to estimate the normalization matrix. Experiment results on image datasets show the presented model can greatly improve the performance of state-of-the-art ResNet backbones by $10-20\%$ at the same level of computing and memory costs.

##### Abstract (translated by Google)
在本文中，我们将使用胶囊向量而不是神经元激活来预测样本标签的胶囊网背后的想法正式化。为此，我们建议学习一组投影输入特征向量的胶囊子空间。然后用合成胶囊的长度来评分属于不同类别的概率。我们通过学习每个胶囊子空间的正交投影矩阵来训练这样的胶囊投影网络（CapProNet），并且显示每个胶囊子空间被更新直到它包含对应于相关类别的输入特征向量。在低维胶囊子空间中训练网络或通过替代的超功率迭代来估计归一化矩阵只会产生微不足道的计算开销。图像数据集上的实验结果表明，所提供的模型可以在相同的计算和内存成本水平下将现有技术的ResNet骨干网的性能大幅提高10-20％。

##### URL
[https://arxiv.org/abs/1805.07621](https://arxiv.org/abs/1805.07621)

##### PDF
[https://arxiv.org/pdf/1805.07621](https://arxiv.org/pdf/1805.07621)

