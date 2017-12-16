---
layout: post
title: "Relaxed Earth Mover's Distances for Chain- and Tree-connected Spaces and their use as a Loss Function in Deep Learning"
date: 2016-11-22 22:54:05
categories: arXiv_CV
tags: arXiv_CV Optimization Deep_Learning Relation
author: Manuel Martinez, Monica Haurilet, Ziad Al-Halah, Makarand Tapaswi, Rainer Stiefelhagen
mathjax: true
---

* content
{:toc}

##### Abstract
The Earth Mover's Distance (EMD) computes the optimal cost of transforming one distribution into another, given a known transport metric between them. In deep learning, the EMD loss allows us to embed information during training about the output space structure like hierarchical or semantic relations. This helps in achieving better output smoothness and generalization. However EMD is computationally expensive.Moreover, solving EMD optimization problems usually require complex techniques like lasso. These properties limit the applicability of EMD-based approaches in large scale machine learning. We address in this work the difficulties facing incorporation of EMD-based loss in deep learning frameworks. Additionally, we provide insight and novel solutions on how to integrate such loss function in training deep neural networks. Specifically, we make three main contributions: (i) we provide an in-depth analysis of the fastest state-of-the-art EMD algorithm (Sinkhorn Distance) and discuss its limitations in deep learning scenarios. (ii) we derive fast and numerically stable closed-form solutions for the EMD gradient in output spaces with chain- and tree- connectivity; and (iii) we propose a relaxed form of the EMD gradient with equivalent computational complexity but faster convergence rate. We support our claims with experiments on real datasets. In a restricted data setting on the ImageNet dataset, we train a model to classify 1000 categories using 50K images, and demonstrate that our relaxed EMD loss achieves better Top-1 accuracy than the cross entropy loss. Overall, we show that our relaxed EMD loss criterion is a powerful asset for deep learning in the small data regime.

##### Abstract (translated by Google)
考虑到它们之间的已知传输度量，地球移动者的距离（EMD）计算将一个分布转换成另一个分布的最优成本。在深度学习中，EMD损失使得我们可以在训练期间嵌入信息，例如分层或者语义关系等输出空间结构。这有助于实现更好的输出平滑度和泛化。然而，EMD在计算上是昂贵的。而且，解决EMD优化问题通常需要复杂的技术，如套索。这些性质限制了基于EMD的方法在大规模机器学习中的适用性。我们在这项工作中解决了在深度学习框架中将基于EMD的损失所面临的困难。此外，我们提供了有关如何在训练深度神经网络中整合这种损失函数的见解和新颖的解决方案。具体来说，我们做了三个主要贡献:(一）我们提供了最先进的最先进的EMD算法（Sinkhorn距离）的深入分析，并讨论它在深度学习场景中的局限性。 （ii）我们推导出具有链和树连通性的输出空间EMD梯度的快速和数值稳定的封闭形式解; （iii）我们提出了一个EMD梯度的松弛形式，其计算复杂度相当，但收敛速度更快。我们通过对真实数据集的实验来支持我们的观点。在ImageNet数据集的受限数据设置中，我们训练一个模型，使用50K图像对1000个类别进行分类，并证明我们的松弛EMD损失比交叉熵损失获得更好的Top-1准确性。总的来说，我们表明，我们宽松的EMD损失标准是在小数据制度下深入学习的有力资产。

##### URL
[https://arxiv.org/abs/1611.07573](https://arxiv.org/abs/1611.07573)

##### PDF
[https://arxiv.org/pdf/1611.07573](https://arxiv.org/pdf/1611.07573)

