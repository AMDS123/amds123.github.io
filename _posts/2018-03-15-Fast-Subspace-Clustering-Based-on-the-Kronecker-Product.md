---
layout: post
title: "Fast Subspace Clustering Based on the Kronecker Product"
date: 2018-03-15 09:31:44
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Optimization
author: Lei Zhou, Xiao Bai, Xianglong Liu, Jun Zhou, Hancock Edwin
mathjax: true
---

* content
{:toc}

##### Abstract
Subspace clustering is a useful technique for many computer vision applications in which the intrinsic dimension of high-dimensional data is often smaller than the ambient dimension. Spectral clustering, as one of the main approaches to subspace clustering, often takes on a sparse representation or a low-rank representation to learn a block diagonal self-representation matrix for subspace generation. However, existing methods require solving a large scale convex optimization problem with a large set of data, with computational complexity reaches O(N^3) for N data points. Therefore, the efficiency and scalability of traditional spectral clustering methods can not be guaranteed for large scale datasets. In this paper, we propose a subspace clustering model based on the Kronecker product. Due to the property that the Kronecker product of a block diagonal matrix with any other matrix is still a block diagonal matrix, we can efficiently learn the representation matrix which is formed by the Kronecker product of k smaller matrices. By doing so, our model significantly reduces the computational complexity to O(kN^{3/k}). Furthermore, our model is general in nature, and can be adapted to different regularization based subspace clustering methods. Experimental results on two public datasets show that our model significantly improves the efficiency compared with several state-of-the-art methods. Moreover, we have conducted experiments on synthetic data to verify the scalability of our model for large scale datasets.

##### Abstract (translated by Google)
子空间聚类是许多计算机视觉应用的有用技术，其中高维数据的固有维数通常小于环境维数。谱聚类作为子空间聚类的主要方法之一，通常采用稀疏表示或低秩表示来学习子空间生成的块对角自我表示矩阵。然而，现有方法需要用大量数据解决大规模凸优化问题，对于N个数据点，计算复杂度达到O（N ^ 3）。因此，传统谱聚类方法的效率和可扩展性不能保证大规模数据集。在本文中，我们提出了一个基于Kronecker产品的子空间聚类模型。由于具有任意其他矩阵的块对角矩阵的克罗内克积仍然是一个块对角矩阵，我们可以有效地学习由k个较小矩阵的Kronecker乘积形成的表示矩阵。通过这样做，我们的模型将计算复杂度显着降低到O（kN ^ {3 / k}）。此外，我们的模型本质上是通用的，并且可以适应不同的基于正则化的子空间聚类方法。两个公共数据集上的实验结果表明，与几种最先进的方法相比，我们的模型显着提高了效率。此外，我们对合成数据进行了实验，以验证我们的模型对于大规模数据集的可扩展性。

##### URL
[https://arxiv.org/abs/1803.05657](https://arxiv.org/abs/1803.05657)

##### PDF
[https://arxiv.org/pdf/1803.05657](https://arxiv.org/pdf/1803.05657)

