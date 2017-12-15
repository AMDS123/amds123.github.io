---
layout: post
title: "Efficient Continuous Relaxations for Dense CRF"
date: 2016-08-22 15:24:25
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Semantic_Segmentation Inference
author: Alban Desmaison, Rudy Bunel, Pushmeet Kohli, Philip H.S. Torr, M. Pawan Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
Dense conditional random fields (CRF) with Gaussian pairwise potentials have emerged as a popular framework for several computer vision applications such as stereo correspondence and semantic segmentation. By modeling long-range interactions, dense CRFs provide a more detailed labelling compared to their sparse counterparts. Variational inference in these dense models is performed using a filtering-based mean-field algorithm in order to obtain a fully-factorized distribution minimising the Kullback-Leibler divergence to the true distribution. In contrast to the continuous relaxation-based energy minimisation algorithms used for sparse CRFs, the mean-field algorithm fails to provide strong theoretical guarantees on the quality of its solutions. To address this deficiency, we show that it is possible to use the same filtering approach to speed-up the optimisation of several continuous relaxations. Specifically, we solve a convex quadratic programming (QP) relaxation using the efficient Frank-Wolfe algorithm. This also allows us to solve difference-of-convex relaxations via the iterative concave-convex procedure where each iteration requires solving a convex QP. Finally, we develop a novel divide-and-conquer method to compute the subgradients of a linear programming relaxation that provides the best theoretical bounds for energy minimisation. We demonstrate the advantage of continuous relaxations over the widely used mean-field algorithm on publicly available datasets.

##### Abstract (translated by Google)
密集条件随机场（CRF）具有高斯成对势能，已经成为几种计算机视觉应用（如立体对应和语义分割）的流行框架。通过对长程相互作用进行建模，密集的CRF比稀疏的CRF提供了更详细的标签。使用基于滤波的平均场算法来执行这些密集模型中的变分推理，以便获得将Kullback-Leibler散度最小化为真实分布的全因子分布。与用于稀疏CRF的基于连续松弛的能量最小化算法相比，平均场算法不能为其解决方案的质量提供强有力的理论保证。为了解决这个缺陷，我们表明可以使用相同的过滤方法来加速几个连续松弛的优化。具体而言，我们使用高效的Frank-Wolfe算法来解决凸二次规划（QP）松弛问题。这也使得我们可以通过迭代的凹凸过程解决凸差的松弛问题，每次迭代需要求解一个凸QP。最后，我们开发了一种新的分而治之的方法来计算线性规划松弛的次梯度，为能量最小化提供了最好的理论界限。我们证明了在广泛使用的公开可用数据集上的平均场算法的连续松弛的优势。

##### URL
[https://arxiv.org/abs/1608.06192](https://arxiv.org/abs/1608.06192)

##### PDF
[https://arxiv.org/pdf/1608.06192](https://arxiv.org/pdf/1608.06192)

