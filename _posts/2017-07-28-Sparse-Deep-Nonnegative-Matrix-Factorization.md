---
layout: post
title: "Sparse Deep Nonnegative Matrix Factorization"
date: 2017-07-28 16:37:37
categories: arXiv_CV
tags: arXiv_CV Sparse Represenation_Learning Classification Deep_Learning Recognition
author: Zhenxing Guo, Shihua Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Nonnegative matrix factorization is a powerful technique to realize dimension reduction and pattern recognition through single-layer data representation learning. Deep learning, however, with its carefully designed hierarchical structure, is able to combine hidden features to form more representative features for pattern recognition. In this paper, we proposed sparse deep nonnegative matrix factorization models to analyze complex data for more accurate classification and better feature interpretation. Such models are designed to learn localized features or generate more discriminative representations for samples in distinct classes by imposing $L_1$-norm penalty on the columns of certain factors. By extending one-layer model into multi-layer one with sparsity, we provided a hierarchical way to analyze big data and extract hidden features intuitively due to nonnegativity. We adopted the Nesterov's accelerated gradient algorithm to accelerate the computing process with the convergence rate of $O(1/k^2)$ after $k$ steps iteration. We also analyzed the computing complexity of our framework to demonstrate their efficiency. To improve the performance of dealing with linearly inseparable data, we also considered to incorporate popular nonlinear functions into this framework and explored their performance. We applied our models onto two benchmarking image datasets, demonstrating our models can achieve competitive or better classification performance and produce intuitive interpretations compared with the typical NMF and competing multi-layer models.

##### Abstract (translated by Google)
非负矩阵分解是通过单层数据表示学习实现降维和模式识别的有力手段。深度学习，但是，其精心设计的分层结构，能够结合隐藏的功能，形成更具代表性的模式识别功能。本文提出了稀疏深度非负矩阵分解模型，对复杂数据进行分析，以更精确的分类和更好的特征解释。这样的模型被设计成通过对某些因子的列施加$ L_1 $ -norm惩罚来学习局部化特征或者为不同类别中的样本产生更多的歧视性表示。通过将稀疏性的单层模型扩展为多层模型，提供了一种分层的方式来分析大数据，并由于非负性而直观地提取隐藏的特征。我们采用了Nesterov加速梯度算法来加速计算过程，迭代次数为$ k $ step后收敛速度为$ O（1 / k ^ 2）$。我们还分析了我们框架的计算复杂性以展示它们的效率。为了提高处理线性不可分的数据的性能，我们也考虑将流行的非线性函数结合到这个框架中，并探讨它们的性能。我们将模型应用到两个基准图像数据集上，证明了我们的模型与典型的NMF和竞争的多层模型相比，可以实现具有竞争力或更好的分类性能，并产生直观的解释。

##### URL
[https://arxiv.org/abs/1707.09316](https://arxiv.org/abs/1707.09316)

##### PDF
[https://arxiv.org/pdf/1707.09316](https://arxiv.org/pdf/1707.09316)

