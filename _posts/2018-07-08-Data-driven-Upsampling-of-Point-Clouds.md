---
layout: post
title: "Data-driven Upsampling of Point Clouds"
date: 2018-07-08 02:19:09
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: Wentai Zhang, Haoliang Jiang, Zhangsihao Yang, Soji Yamakawa, Kenji Shimada, Levent Burak Kara
mathjax: true
---

* content
{:toc}

##### Abstract
High quality upsampling of sparse 3D point clouds is critically useful for a wide range of geometric operations such as reconstruction, rendering, meshing, and analysis. In this paper, we propose a data-driven algorithm that enables an upsampling of 3D point clouds without the need for hard-coded rules. Our approach uses a deep network with Chamfer distance as the loss function, capable of learning the latent features in point clouds belonging to different object categories. We evaluate our algorithm across different amplification factors, with upsampling learned and performed on objects belonging to the same category as well as different categories. We also explore the desirable characteristics of input point clouds as a function of the distribution of the point samples. Finally, we demonstrate the performance of our algorithm in single-category training versus multi-category training scenarios. The final proposed model is compared against a baseline, optimization-based upsampling method. Results indicate that our algorithm is capable of generating more uniform and accurate upsamplings.

##### Abstract (translated by Google)
稀疏3D点云的高质量上采样对于各种几何操作（例如重建，渲染，网格划分和分析）非常有用。在本文中，我们提出了一种数据驱动算法，该算法能够在不需要硬编码规则的情况下对3D点云进行上采样。我们的方法使用具有倒角距离的深度网络作为损失函数，能够学习属于不同对象类别的点云中的潜在特征。我们在不同的放大因子上评估我们的算法，对属于同一类别和不同类别的对象学习和执行上采样。我们还探索了输入点云的理想特性，作为点样本分布的函数。最后，我们演示了我们的算法在单类训练和多类训练场景中的表现。将最终提出的模型与基线，基于优化的上采样方法进行比较。结果表明我们的算法能够产生更均匀和准确的上采样。

##### URL
[http://arxiv.org/abs/1807.02740](http://arxiv.org/abs/1807.02740)

##### PDF
[http://arxiv.org/pdf/1807.02740](http://arxiv.org/pdf/1807.02740)

