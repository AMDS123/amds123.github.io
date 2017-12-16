---
layout: post
title: "Locality preserving projection on SPD matrix Lie group: algorithm and analysis"
date: 2017-11-16 02:47:32
categories: arXiv_CV
tags: arXiv_CV Face Action_Recognition Recognition Face_Recognition
author: Yangyang Li, Ruqian Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Symmetric positive definite (SPD) matrices used as feature descriptors in image recognition are usually high dimensional. Traditional manifold learning is only applicable for reducing the dimension of high-dimensional vector-form data. For high-dimensional SPD matrices, directly using manifold learning algorithms to reduce the dimension of matrix-form data is impossible. The SPD matrix must first be transformed into a long vector, and then the dimension of this vector must be reduced. However, this approach breaks the spatial structure of the SPD matrix space. To overcome this limitation, we propose a new dimension reduction algorithm on SPD matrix space to transform high-dimensional SPD matrices into low-dimensional SPD matrices. Our work is based on the fact that the set of all SPD matrices with the same size has a Lie group structure, and we aim to transform the manifold learning to the SPD matrix Lie group. We use the basic idea of the manifold learning algorithm called locality preserving projection (LPP) to construct the corresponding Laplacian matrix on the SPD matrix Lie group. Thus, we call our approach Lie-LPP to emphasize its Lie group character. We present a detailed algorithm analysis and show through experiments that Lie-LPP achieves effective results on human action recognition and human face recognition.

##### Abstract (translated by Google)
在图像识别中用作特征描述符的对称正定（SPD）矩阵通常是高维的。传统的流形学习只适用于降维矢量形式的高维数据。对于高维SPD矩阵，直接使用流形学习算法来减少矩阵形式数据的维数是不可能的。必须先将SPD矩阵转换成长向量，然后减小该向量的维数。但是，这种方法打破了SPD矩阵空间的空间结构。为了克服这个局限性，我们提出了一种新的SPD矩阵空间降维算法，将高维SPD矩阵转换为低维SPD矩阵。我们的工作基于这样一个事实，即具有相同大小的所有SPD矩阵的集合具有李群结构，我们的目标是将流形学习转换为SPD矩阵李群。我们使用流形学习算法的基本思想，称为局部保持投影（LPP），在SPD矩阵李群上构造相应的拉普拉斯矩阵。因此，我们把我们的方法称为Lie-LPP来强调它的李群性格。我们给出了详细的算法分析，并通过实验证明了Lie-LPP在人体动作识别和人脸识别方面取得了有效的结果。

##### URL
[https://arxiv.org/abs/1703.09499](https://arxiv.org/abs/1703.09499)

##### PDF
[https://arxiv.org/pdf/1703.09499](https://arxiv.org/pdf/1703.09499)

