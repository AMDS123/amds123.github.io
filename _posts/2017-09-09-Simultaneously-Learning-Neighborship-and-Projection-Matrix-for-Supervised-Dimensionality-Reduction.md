---
layout: post
title: "Simultaneously Learning Neighborship and Projection Matrix for Supervised Dimensionality Reduction"
date: 2017-09-09 02:44:18
categories: arXiv_CV
tags: arXiv_CV Regularization Classification
author: Yanwei Pang, Bo Zhou, Feiping Nie
mathjax: true
---

* content
{:toc}

##### Abstract
Explicitly or implicitly, most of dimensionality reduction methods need to determine which samples are neighbors and the similarity between the neighbors in the original highdimensional space. The projection matrix is then learned on the assumption that the neighborhood information (e.g., the similarity) is known and fixed prior to learning. However, it is difficult to precisely measure the intrinsic similarity of samples in high-dimensional space because of the curse of dimensionality. Consequently, the neighbors selected according to such similarity might and the projection matrix obtained according to such similarity and neighbors are not optimal in the sense of classification and generalization. To overcome the drawbacks, in this paper we propose to let the similarity and neighbors be variables and model them in low-dimensional space. Both the optimal similarity and projection matrix are obtained by minimizing a unified objective function. Nonnegative and sum-to-one constraints on the similarity are adopted. Instead of empirically setting the regularization parameter, we treat it as a variable to be optimized. It is interesting that the optimal regularization parameter is adaptive to the neighbors in low-dimensional space and has intuitive meaning. Experimental results on the YALE B, COIL-100, and MNIST datasets demonstrate the effectiveness of the proposed method.

##### Abstract (translated by Google)
显式或隐式地，大多数降维方法都需要确定哪些样本是邻居，以及原始高维空间中邻居之间的相似度。然后在假设邻近信息（例如，相似度）在学习之前已知并固定的情况下学习投影矩阵。但是，由于维数的诅咒，很难精确地测量高维空间中样本的内在相似性。因此，根据这样的相似性选择的邻居可能和根据这样的相似度和邻居获得的投影矩阵在分类和泛化意义上不是最佳的。为了克服这些缺点，本文提出将相似度和邻居作为变量，并在低维空间中进行建模。通过最小化统一的目标函数来获得最佳相似度和投影矩阵。采用非负性和相似性约束。我们不是根据经验设定正则化参数，而是将其作为一个变量进行优化。有趣的是，最优正则化参数适应于低维空间中的邻居，具有直观的意义。在YALE B，COIL-100和MNIST数据集上的实验结果证明了所提出的方法的有效性。

##### URL
[https://arxiv.org/abs/1709.02896](https://arxiv.org/abs/1709.02896)

##### PDF
[https://arxiv.org/pdf/1709.02896](https://arxiv.org/pdf/1709.02896)

