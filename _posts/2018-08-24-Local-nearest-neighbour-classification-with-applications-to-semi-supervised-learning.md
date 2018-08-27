---
layout: post
title: "Local nearest neighbour classification with applications to semi-supervised learning"
date: 2018-08-24 11:16:30
categories: arXiv_CV
tags: arXiv_CV Classification
author: Timothy I. Cannings, Thomas B. Berrett, Richard J. Samworth
mathjax: true
---

* content
{:toc}

##### Abstract
We derive a new asymptotic expansion for the global excess risk of a local $k$-nearest neighbour classifier, where the choice of $k$ may depend upon the test point. This expansion elucidates conditions under which the dominant contribution to the excess risk comes from the locus of points at which each class label is equally likely to occur, but we also show that if these conditions are not satisfied, the dominant contribution may arise from the tails of the marginal distribution of the features. Moreover, we prove that, provided the $d$-dimensional marginal distribution of the features has a finite $\rho$th moment for some $\rho &gt; 4$ (as well as other regularity conditions), a local choice of $k$ can yield a rate of convergence of the excess risk of $O(n^{-4/(d+4)})$, where $n$ is the sample size, whereas for the standard $k$-nearest neighbour classifier, our theory would require $d \geq 5$ and $\rho &gt; 4d/(d-4)$ finite moments to achieve this rate. Our results motivate a new $k$-nearest neighbour classifier for semi-supervised learning problems, where the unlabelled data are used to obtain an estimate of the marginal feature density, and fewer neighbours are used for classification when this density estimate is small. The potential improvements over the standard $k$-nearest neighbour classifier are illustrated both through our theory and via a simulation study.

##### Abstract (translated by Google)
我们推导出一个新的渐近扩展，用于本地$ k $最近邻分类器的全局超额风险，其中$ k $的选择可能取决于测试点。这种扩展阐明了对超额风险的主要贡献来自每个类别标签同样可能发生的点的位置的条件，但我们也表明，如果不满足这些条件，则可能由尾部产生主导贡献。特征的边际分布。此外，我们证明，如果特征的$ d $ -dimensional边际分布对于某些$ \ rho>具有有限的$ \ rho $ th时刻。 4 $（以及其他常规条件），当地选择$ k $可以产生$ O（n ^ { -  4 /（d + 4）}）$的超额风险收敛率，其中$ n $是样本大小，而对于标准的$ k $最近邻分类器，我们的理论需要$ d \ geq 5 $和$ \ rho＆gt; 4d /（d-4）$有限时刻达到这个速度。我们的结果激发了一个新的$ k $最近邻分类器用于半监督学习问题，其中未标记数据用于获得边际特征密度的估计，并且当该密度估计较小时用于分类的邻居较少。通过我们的理论和模拟研究，说明了对标准$ k $最近邻分类器的潜在改进。

##### URL
[http://arxiv.org/abs/1704.00642](http://arxiv.org/abs/1704.00642)

##### PDF
[http://arxiv.org/pdf/1704.00642](http://arxiv.org/pdf/1704.00642)

