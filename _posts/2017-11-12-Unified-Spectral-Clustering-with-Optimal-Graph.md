---
layout: post
title: "Unified Spectral Clustering with Optimal Graph"
date: 2017-11-12 09:20:25
categories: arXiv_CV
tags: arXiv_CV
author: Zhao Kang, Chong Peng, Qiang Cheng, Zenglin Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Spectral clustering has found extensive use in many areas. Most traditional spectral clustering algorithms work in three separate steps: similarity graph construction; continuous labels learning; discretizing the learned labels by k-means clustering. Such common practice has two potential flaws, which may lead to severe information loss and performance degradation. First, predefined similarity graph might not be optimal for subsequent clustering. It is well-accepted that similarity graph highly affects the clustering results. To this end, we propose to automatically learn similarity information from data and simultaneously consider the constraint that the similarity matrix has exact c connected components if there are c clusters. Second, the discrete solution may deviate from the spectral solution since k-means method is well-known as sensitive to the initialization of cluster centers. In this work, we transform the candidate solution into a new one that better approximates the discrete one. Finally, those three subtasks are integrated into a unified framework, with each subtask iteratively boosted by using the results of the others towards an overall optimal solution. It is known that the performance of a kernel method is largely determined by the choice of kernels. To tackle this practical problem of how to select the most suitable kernel for a particular data set, we further extend our model to incorporate multiple kernel learning ability. Extensive experiments demonstrate the superiority of our proposed method as compared to existing clustering approaches.

##### Abstract (translated by Google)
光谱聚类已经在许多领域得到广泛的应用。大多数传统的谱聚类算法分三个步骤工作：相似图构建;连续标签学习;通过k-means聚类来离散学习的标签。这种常见的做法有两个潜在的缺陷，可能会导致严重的信息丢失和性能下降。首先，预定义的相似度图可能不是最佳的后续聚类。相似度图高度影响聚类结果是公认的。为此，我们提出从数据中自动学习相似性信息，同时考虑相似矩阵具有c个连续分量的约束条件。其次，离散解可能偏离谱解，因为k-均值方法对于聚类中心的初始化是敏感的。在这项工作中，我们将候选方案转化为一个更接近离散方案的新方案。最后，将这三个子任务整合到一个统一的框架中，每个子任务通过使用其他任务的结果迭代地提升到一个整体最优解。众所周知，内核方法的性能在很大程度上取决于内核的选择。为了解决如何为特定的数据集选择最合适的内核这一实际问题，我们进一步扩展了我们的模型以结合多个内核学习能力。大量的实验证明了我们提出的方法与现有的聚类方法相比的优越性。

##### URL
[https://arxiv.org/abs/1711.04258](https://arxiv.org/abs/1711.04258)

##### PDF
[https://arxiv.org/pdf/1711.04258](https://arxiv.org/pdf/1711.04258)

