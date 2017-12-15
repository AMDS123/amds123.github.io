---
layout: post
title: "Swivel: Improving Embeddings by Noticing What's Missing"
date: 2016-02-06 04:39:41
categories: arXiv_SD
tags: arXiv_SD Embedding Gradient_Descent
author: Noam Shazeer, Ryan Doherty, Colin Evans, Chris Waterson
mathjax: true
---

* content
{:toc}

##### Abstract
We present Submatrix-wise Vector Embedding Learner (Swivel), a method for generating low-dimensional feature embeddings from a feature co-occurrence matrix. Swivel performs approximate factorization of the point-wise mutual information matrix via stochastic gradient descent. It uses a piecewise loss with special handling for unobserved co-occurrences, and thus makes use of all the information in the matrix. While this requires computation proportional to the size of the entire matrix, we make use of vectorized multiplication to process thousands of rows and columns at once to compute millions of predicted values. Furthermore, we partition the matrix into shards in order to parallelize the computation across many nodes. This approach results in more accurate embeddings than can be achieved with methods that consider only observed co-occurrences, and can scale to much larger corpora than can be handled with sampling methods.

##### Abstract (translated by Google)
我们提出子矩阵明智的矢量嵌入学习者（旋转），一种从特征共生矩阵生成低维特征嵌入的方法。旋转通过随机梯度下降来执行对点的互信息矩阵的近似因式分解。它使用分段丢失和特殊处理来观察未知的共现，从而利用矩阵中的所有信息。虽然这需要与整个矩阵的大小成比例的计算，但是我们利用矢量化乘法来一次处理数千行和列以计算数百万个预测值。此外，我们将矩阵分成碎片，以便跨越多个节点并行化计算。这种方法导致比使用仅考虑共现的方法可以实现更精确的嵌入，并且可以扩展到比采样方法更大的语料库。

##### URL
[https://arxiv.org/abs/1602.02215](https://arxiv.org/abs/1602.02215)

##### PDF
[https://arxiv.org/pdf/1602.02215](https://arxiv.org/pdf/1602.02215)

