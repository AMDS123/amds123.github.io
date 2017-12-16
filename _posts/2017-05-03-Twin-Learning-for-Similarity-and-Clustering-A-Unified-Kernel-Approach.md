---
layout: post
title: "Twin Learning for Similarity and Clustering: A Unified Kernel Approach"
date: 2017-05-03 00:29:13
categories: arXiv_CV
tags: arXiv_CV Relation
author: Zhao Kang, Chong Peng, Qiang Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
Many similarity-based clustering methods work in two separate steps including similarity matrix computation and subsequent spectral clustering. However, similarity measurement is challenging because it is usually impacted by many factors, e.g., the choice of similarity metric, neighborhood size, scale of data, noise and outliers. Thus the learned similarity matrix is often not suitable, let alone optimal, for the subsequent clustering. In addition, nonlinear similarity often exists in many real world data which, however, has not been effectively considered by most existing methods. To tackle these two challenges, we propose a model to simultaneously learn cluster indicator matrix and similarity information in kernel spaces in a principled way. We show theoretical relationships to kernel k-means, k-means, and spectral clustering methods. Then, to address the practical issue of how to select the most suitable kernel for a particular clustering task, we further extend our model with a multiple kernel learning ability. With this joint model, we can automatically accomplish three subtasks of finding the best cluster indicator matrix, the most accurate similarity relations and the optimal combination of multiple kernels. By leveraging the interactions between these three subtasks in a joint framework, each subtask can be iteratively boosted by using the results of the others towards an overall optimal solution. Extensive experiments are performed to demonstrate the effectiveness of our method.

##### Abstract (translated by Google)
许多基于相似性的聚类方法分两个步骤进行，包括相似度矩阵计算和随后的谱聚类。然而，相似性测量是具有挑战性的，因为它通常受许多因素影响，例如相似性度量的选择，邻域大小，数据的规模，噪声和异常值。因此学习的相似度矩阵往往不适合，更不用说最优化，以便后续的聚类。另外，在许多现实世界的数据中经常存在非线性相似性，然而大多数现有方法尚未有效地考虑非线性相似性。针对这两个挑战，我们提出了一个同时学习核心空间中的聚类指标矩阵和相似度信息的模型。我们展示了核心k均值，k均值和谱聚类方法的理论关系。然后，为了解决如何为特定的聚类任务选择最合适的内核的实际问题，我们进一步扩展了我们的模型的多核学习能力。利用这种联合模型，可以自动完成三个子任务，找出最佳聚类指标矩阵，最准确的相似关系和多个最优组合。通过在一个联合框架中利用这三个子任务之间的交互作用，每个子任务可以通过使用其他任务的结果来迭代地提升，以达到整体最优解。进行大量的实验来证明我们的方法的有效性。

##### URL
[https://arxiv.org/abs/1705.00678](https://arxiv.org/abs/1705.00678)

##### PDF
[https://arxiv.org/pdf/1705.00678](https://arxiv.org/pdf/1705.00678)

