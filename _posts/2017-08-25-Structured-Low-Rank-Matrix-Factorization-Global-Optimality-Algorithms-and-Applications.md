---
layout: post
title: "Structured Low-Rank Matrix Factorization: Global Optimality, Algorithms, and Applications"
date: 2017-08-25 18:14:44
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Attention Optimization
author: Benjamin D. Haeffele, Rene Vidal
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, convex formulations of low-rank matrix factorization problems have received considerable attention in machine learning. However, such formulations often require solving for a matrix of the size of the data matrix, making it challenging to apply them to large scale datasets. Moreover, in many applications the data can display structures beyond simply being low-rank, e.g., images and videos present complex spatio-temporal structures that are largely ignored by standard low-rank methods. In this paper we study a matrix factorization technique that is suitable for large datasets and captures additional structure in the factors by using a particular form of regularization that includes well-known regularizers such as total variation and the nuclear norm as particular cases. Although the resulting optimization problem is non-convex, we show that if the size of the factors is large enough, under certain conditions, any local minimizer for the factors yields a global minimizer. A few practical algorithms are also provided to solve the matrix factorization problem, and bounds on the distance from a given approximate solution of the optimization problem to the global optimum are derived. Examples in neural calcium imaging video segmentation and hyperspectral compressed recovery show the advantages of our approach on high-dimensional datasets.

##### Abstract (translated by Google)
最近，低秩矩阵分解问题的凸形式在机器学习中受到了相当的关注。然而，这样的表达式通常需要求解数据矩阵大小的矩阵，使得将其应用于大规模数据集具有挑战性。此外，在许多应用中，数据可以显示不仅仅是低级别的结构，例如图像和视频呈现复杂的时空结构，其被标准的低级方法大部分忽略。在本文中，我们研究了适用于大数据集的矩阵分解技术，并通过使用特定形式的正则化来捕获因子中的附加结构，所述正则化包括众所周知的正则化因子，例如总变化和作为特定情况的核准则。虽然最终的优化问题是非凸的，但是我们证明了如果因子的大小足够大，在某些条件下，因子的任何局部最小值都会产生一个全局最小值。本文还提出了一些实用的算法来解决矩阵分解问题，推导了求解优化问题到全局最优解的距离的界限。神经钙成像视频分割和高光谱压缩恢复的实例显示了我们的方法在高维数据集上的优势。

##### URL
[https://arxiv.org/abs/1708.07850](https://arxiv.org/abs/1708.07850)

##### PDF
[https://arxiv.org/pdf/1708.07850](https://arxiv.org/pdf/1708.07850)

