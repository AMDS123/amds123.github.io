---
layout: post
title: "Local nearest neighbour classification with applications to semi-supervised learning"
date: 2017-04-03 15:34:11
categories: arXiv_CV
tags: arXiv_CV Classification
author: Timothy I. Cannings, Thomas B. Berrett, Richard J. Samworth
mathjax: true
---

* content
{:toc}

##### Abstract
We derive a new asymptotic expansion for the global excess risk of a local $k$-nearest neighbour classifier, where the choice of $k$ may depend upon the test point. This expansion elucidates conditions under which the dominant contribution to the excess risk comes from the locus of points at which each class label is equally likely to occur, but we also show that if these conditions are not satisfied, the dominant contribution may arise from the tails of the marginal distribution of the features. Moreover, we prove that, provided the $d$-dimensional marginal distribution of the features has a finite $\rho$th moment for some $\rho > 4$ (as well as other regularity conditions), a local choice of $k$ can yield a rate of convergence of the excess risk of $O(n^{-4/(d+4)})$, where $n$ is the sample size, whereas for the standard $k$-nearest neighbour classifier, our theory would require $d \geq 5$ and $\rho > 4d/(d-4)$ finite moments to achieve this rate. Our results motivate a new $k$-nearest neighbour classifier for semi-supervised learning problems, where the unlabelled data are used to obtain an estimate of the marginal feature density, and fewer neighbours are used for classification when this density estimate is small. The potential improvements over the standard $k$-nearest neighbour classifier are illustrated both through our theory and via a simulation study.

##### Abstract (translated by Google)
我们推导出一个新的渐进式扩展，用于一个局部$ k $  - 最近邻分类器的全局超额风险，其中$ k $的选择可能取决于测试点。这种扩展阐明了对过剩风险的主要贡献来自每个类别标签同样可能发生的点的轨迹的条件，但是我们也表明，如果这些条件不满足，主导贡献可能来自尾部的特征的边缘分布。此外，我们证明，如果特征的$ d $  - 维的边际分布对于一些$ \ rho> $（以及其他正则条件）具有有限的$ \ rho $ th矩，则$ k $可以产生$ O（n ^ { -  4 /（d + 4）}）$的超额风险的收敛速度，其中$ n $是样本大小，而对于标准$ k $  - 最近邻居分类器，我们的理论将需要$ d \ geq 5 $和$ 4d /（d-4）$有限矩来达到这个速度。我们的结果激发了一个新的$ k $  - 最近的邻居分类器的半监督学习问题，其中未标记的数据用于获得边缘特征密度的估计，较少的邻居用于分类，当这种密度估计很小。通过我们的理论和通过模拟研究来说明对标准$ k $  - 最近的邻居分类器的潜在改进。

##### URL
[https://arxiv.org/abs/1704.00642](https://arxiv.org/abs/1704.00642)

##### PDF
[https://arxiv.org/pdf/1704.00642](https://arxiv.org/pdf/1704.00642)

