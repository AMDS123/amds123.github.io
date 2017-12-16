---
layout: post
title: "Deep manifold-to-manifold transforming network for action recognition"
date: 2017-09-30 03:09:53
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Classification Relation Recognition
author: Tong Zhang (1 and 2), Wenming Zheng (2), Zhen Cui (3), Chaolong Li (2) ((1) the Department of Information Science and Engineering, Southeast University, Nanjing, China (2) the Key Laboratory of Child Development and Learning Science of Ministry of Education, Research Center for Learning Science, Southeast University, Nanjing, China (3) School of Computer Science and Engineering, Nanjing University of Science and Technology, Nanjing, China)
mathjax: true
---

* content
{:toc}

##### Abstract
Symmetric positive definite (SPD) matrices (e.g., covariances, graph Laplacians, etc.) are widely used to model the relationship of spatial or temporal domain. Nevertheless, SPD matrices are theoretically embedded on Riemannian manifolds. In this paper, we propose an end-to-end deep manifold-to-manifold transforming network (DMT-Net) which can make SPD matrices flow from one Riemannian manifold to another more discriminative one. To learn discriminative SPD features characterizing both spatial and temporal dependencies, we specifically develop three novel layers on manifolds: (i) the local SPD convolutional layer, (ii) the non-linear SPD activation layer, and (iii) the Riemannian-preserved recursive layer. The SPD property is preserved through all layers without any requirement of singular value decomposition (SVD), which is often used in the existing methods with expensive computation cost. Furthermore, a diagonalizing SPD layer is designed to efficiently calculate the final metric for the classification task. To evaluate our proposed method, we conduct extensive experiments on the task of action recognition, where input signals are popularly modeled as SPD matrices. The experimental results demonstrate that our DMT-Net is much more competitive over state-of-the-art.

##### Abstract (translated by Google)
对称正定（SPD）矩阵（例如协方差，图拉普拉斯等）被广泛用于对空间或时间域的关系进行建模。尽管如此，SPD矩阵理论上是嵌在黎曼流形上的。在本文中，我们提出了一个端到端深的流形到流形变换网络（DMT-Net），它可以使SPD矩阵从一个黎曼流形流向另一个更具辨别性的网络。为了学习辨别SPD特征的空间和时间依赖性，我们在流形上特别开发了三个新的层：（i）局部SPD卷积层，（ii）非线性SPD激活层，和（iii）黎曼保留递归层。 SPD属性保留在所有层中，不需要任何奇异值分解（SVD）的要求，奇异值分解（SVD）在现有方法中经常使用，计算成本昂贵。此外，对角化SPD层被设计为有效地计算分类任务的最终度量。为了评估我们提出的方法，我们对动作识别的任务进行了广泛的实验，其中输入信号被普遍地建模为SPD矩阵。实验结果表明，我们的DMT-Net比现有技术更具竞争力。

##### URL
[https://arxiv.org/abs/1705.10732](https://arxiv.org/abs/1705.10732)

##### PDF
[https://arxiv.org/pdf/1705.10732](https://arxiv.org/pdf/1705.10732)

