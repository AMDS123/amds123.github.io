---
layout: post
title: "Outlier Regularization for Vector Data and L21 Norm Robustness"
date: 2017-06-20 13:20:11
categories: arXiv_CV
tags: arXiv_CV Regularization Prediction
author: Bo Jiang, Chris Ding
mathjax: true
---

* content
{:toc}

##### Abstract
In many real-world applications, data usually contain outliers. One popular approach is to use L2,1 norm function as a robust error/loss function. However, the robustness of L2,1 norm function is not well understood so far. In this paper, we propose a new Vector Outlier Regularization (VOR) framework to understand and analyze the robustness of L2,1 norm function. Our VOR function defines a data point to be outlier if it is outside a threshold with respect to a theoretical prediction, and regularize it-pull it back to the threshold line. We then prove that L2,1 function is the limiting case of this VOR with the usual least square/L2 error function as the threshold shrinks to zero. One interesting property of VOR is that how far an outlier lies away from its theoretically predicted value does not affect the final regularization and analysis results. This VOR property unmasks one of the most peculiar property of L2,1 norm function: The effects of outliers seem to be independent of how outlying they are-if an outlier is moved further away from the intrinsic manifold/subspace, the final analysis results do not change. VOR provides a new way to understand and analyze the robustness of L2,1 norm function. Applying VOR to matrix factorization leads to a new VORPCA model. We give a comprehensive comparison with trace-norm based L21-norm PCA to demonstrate the advantages of VORPCA.

##### Abstract (translated by Google)
在许多实际应用中，数据通常包含异常值。一种流行的方法是使用L2,1范数函数作为鲁棒的错误/丢失函数。然而，L2,1范数函数的鲁棒性到目前为止还不是很好理解。在本文中，我们提出了一个新的矢量异常值正则化（VOR）框架来理解和分析L2,1范数函数的鲁棒性。我们的VOR函数定义了一个数据点，如果这个数据点在理论预测的阈值之外，那么这个数据点是异常的，并且将其调整 - 将其拉回阈值线。然后我们证明L2,1函数是这个VOR的极限情况，当阈值收缩到零时，它具有通常的最小二乘/ L2误差函数。 VOR的一个有趣的特性是异常值远离其理论预测值的程度不会影响最终的正则化和分析结果。这个VOR属性揭示了L2,1范数函数最独特的性质之一：异常值的影响似乎与它们的偏离无关 - 如果异常值远离本征流形/子空间，最终的分析结果会做不变。 VOR为理解和分析L2,1范数函数的鲁棒性提供了一种新的途径。将VOR应用于矩阵分解导致新的VORPCA模型。我们综合比较了基于trace范数的L21范数PCA来展示VORPCA的优势。

##### URL
[https://arxiv.org/abs/1706.06409](https://arxiv.org/abs/1706.06409)

##### PDF
[https://arxiv.org/pdf/1706.06409](https://arxiv.org/pdf/1706.06409)

