---
layout: post
title: "Coresets for Triangulation"
date: 2017-07-18 04:47:31
categories: arXiv_CV
tags: arXiv_CV
author: Qianggong Zhang, Tat-Jun Chin
mathjax: true
---

* content
{:toc}

##### Abstract
Multiple-view triangulation by $\ell_{\infty}$ minimisation has become established in computer vision. State-of-the-art $\ell_{\infty}$ triangulation algorithms exploit the quasiconvexity of the cost function to derive iterative update rules that deliver the global minimum. Such algorithms, however, can be computationally costly for large problem instances that contain many image measurements, e.g., from web-based photo sharing sites or long-term video recordings. In this paper, we prove that $\ell_{\infty}$ triangulation admits a coreset approximation scheme, which seeks small representative subsets of the input data called coresets. A coreset possesses the special property that the error of the $\ell_{\infty}$ solution on the coreset is within known bounds from the global minimum. We establish the necessary mathematical underpinnings of the coreset algorithm, specifically, by enacting the stopping criterion of the algorithm and proving that the resulting coreset gives the desired approximation accuracy. On large-scale triangulation problems, our method provides theoretically sound approximate solutions. Iterated until convergence, our coreset algorithm is also guaranteed to reach the true optimum. On practical datasets, we show that our technique can in fact attain the global minimiser much faster than current methods

##### Abstract (translated by Google)
在计算机视觉中已经建立了由$ \ ell _ {\ infty} $ minimization进行的多视图三角测量。最先进的$ \ ell _ {\ infty} $三角剖分算法利用成本函数的拟凸性来导出提供全局最小值的迭代更新规则。然而，这样的算法对于包含许多图像测量的大问题实例（例如，基于网页的照片共享站点或长期视频记录）在计算上可能是昂贵的。在本文中，我们证明$ \ ell \ {\ infty} $三角测量承认核心集近似方案，寻找输入数据的小代表性子集称为核心集。核心集具有核心集上的$ \ ell _ {\ infty} $解的误差在全局最小值范围内的特殊属性。我们建立核心算法的必要的数学基础，具体来说，通过制定算法的停止标准，并证明由此产生的核心集给出所需的近似精度。在大规模三角测量问题上，我们的方法提供了理论上合理的近似解。迭代直到收敛，我们的核心算法也保证达到真正的最优。在实际的数据集上，我们表明，我们的技术实际上可以比当前的方法快得多的全局最小化

##### URL
[https://arxiv.org/abs/1707.05466](https://arxiv.org/abs/1707.05466)

##### PDF
[https://arxiv.org/pdf/1707.05466](https://arxiv.org/pdf/1707.05466)

