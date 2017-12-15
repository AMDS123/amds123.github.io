---
layout: post
title: "Parameterized Principal Component Analysis"
date: 2017-05-02 19:16:36
categories: arXiv_CV
tags: arXiv_CV Sparse Face Optimization
author: Ajay Gupta, Adrian Barbu
mathjax: true
---

* content
{:toc}

##### Abstract
When modeling multivariate data, one might have an extra parameter of contextual information that could be used to treat some observations as more similar to others. For example, images of faces can vary by age, and one would expect the face of a 40 year old to be more similar to the face of a 30 year old than to a baby face. We introduce a novel manifold approximation method, parameterized principal component analysis (PPCA) that models data with linear subspaces that change continuously according to the extra parameter of contextual information (e.g. age), instead of ad-hoc atlases. Special care has been taken in the loss function and the optimization method to encourage smoothly changing subspaces across the parameter values. The approach ensures that each observation's projection will share information with observations that have similar parameter values, but not with observations that have large parameter differences. We tested PPCA on artificial data based on known, smooth functions of an added parameter, as well as on three real datasets with different types of parameters. We compared PPCA to PCA, sparse PCA and to independent principal component analysis (IPCA), which groups observations by their parameter values and projects each group using PCA with no sharing of information for different groups. PPCA recovers the known functions with less error and projects the datasets' test set observations with consistently less reconstruction error than IPCA does. In some cases where the manifold is truly nonlinear, PCA outperforms all the other manifold approximation methods compared.

##### Abstract (translated by Google)
在对多元数据进行建模时，可能会有一个额外的上下文信息参数，可以用来将某些观察值与其他参数相比较。例如，脸部的图像会因年龄而有所不同，人们可能会认为40岁的脸部比30岁的脸部更像脸部。我们引入了一种新颖的流形逼近方法，参数化主成分分析（PPCA），该模型用线性子空间根据上下文信息（例如年龄）的额外参数连续变化的数据进行建模，而不是临时地图集。在损失函数和优化方法中已经采取了特别的措施来鼓励平滑地改变参数值的子空间。该方法确保每个观测的投影将与具有相似参数值的观测值共享信息，但不与具有大参数差异的观测值共享信息。我们测试PPCA基于已知的，平滑的功能的一个附加参数的人工数据，以及三个具有不同类型参数的真实数据集。我们比较了PPCA与PCA，稀疏PCA和独立主成分分析（IPCA），它们按照其参数值对观测进行分组，并使用PCA对每个组进行投影，而不分组不同的信息。 PPCA以较少的误差恢复已知的函数，并且与IPCA相比，一致地减少重建误差来投影数据集的测试集观察值。在一些情况下，流形是真正的非线性，PCA胜过所有其他流形近似方法比较。

##### URL
[https://arxiv.org/abs/1608.04695](https://arxiv.org/abs/1608.04695)

##### PDF
[https://arxiv.org/pdf/1608.04695](https://arxiv.org/pdf/1608.04695)

