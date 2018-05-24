---
layout: post
title: "Efficient Relaxations for Dense CRFs with Sparse Higher Order Potentials"
date: 2018-05-23 09:34:51
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Semantic_Segmentation Inference
author: Thomas Joy, Alban Desmaison, Thalaiyasingam Ajanthan, Rudy Bunel, Mathieu Salzmann, Pushmeet Kohli, Philip H.S. Torr, M. Pawan Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
Dense conditional random fields (CRFs) with Gaussian pairwise potentials have become a popular framework for modelling several problems in computer vision such as stereo correspondence and multi-class semantic segmentation. By modelling long-range interactions, dense CRFs provide a more detailed labelling compared to their sparse counterparts. Currently the state-of-the-art algorithm performs mean-field inference using a filter-based method to obtain accurate segmentations, but fails to provide strong theoretical guarantees on the quality of the solution. Whilst the underlying model of a dense CRF provides enough information to yield well defined segmentations, it lacks the richness introduced via higher order potentials. The mean-field inference strategy was also extended to incorporate higher order potentials, but again failed to obtain a bound on the quality of the solution. To this extent, we show that a dense CRF can be aggregated with sparse higher order potentials in a way that is amenable to continuous relaxations. We will then show that, by using a filter-based method, these continuous relaxations can be optimised efficiently using state-of-the-art algorithms. Specifically we will solve a quadratic programming (QP) relaxation using the Frank-Wolfe algorithm and a linear programming (LP) relaxation by developing a proximal minimisation framework. By exploiting labelling consistency in the higher order potentials and utilising the filter-based method, we are able to formulate the above algorithms such that each iteration has a complexity linear in the number of classes and random variables. The experiments are performed on the standard publicly available MSRC data set and demonstrate the low energies achieved from the minimisation and the accuracy of the resulting segmentations.

##### Abstract (translated by Google)
具有高斯成对电势的稠密条件随机场（CRF）已经成为模拟计算机视觉中的几个问题的流行框架，例如立体对应和多类别语义分割。通过对长程相互作用进行建模，密集的CRF与稀疏的CRF相比可提供更详细的标签。目前，最先进的算法使用基于滤波器的方法执行平均场推断以获得准确的分段，但未能对解决方案的质量提供强有力的理论保证。虽然密集的CRF的基本模型提供了足够的信息来产生明确的分割，但它缺乏通过更高阶潜能引入的丰富性。平均场推断策略也被扩展到包含更高阶的潜力，但再次未能获得解决方案质量的界限。就此而言，我们表明密集的CRF可以以适合持续放松的方式与稀疏的更高阶潜能集合。然后我们将展示，通过使用基于过滤器的方法，可以使用最先进的算法有效地优化这些连续松弛。具体而言，我们将使用Frank-Wolfe算法解决二次规划（QP）松弛问题，并通过开发近端最小化框架解决线性规划（LP）松弛问题。通过利用更高阶潜能中的标记一致性和利用基于滤波器的方法，我们能够制定上述算法，使得每次迭代在类和随机变量的数量上具有线性复杂性。实验是在标准的公开可用的MSRC数据集上进行的，并且证明了由最小化和所得到的分段的准确性所实现的低能量。

##### URL
[http://arxiv.org/abs/1805.09028](http://arxiv.org/abs/1805.09028)

##### PDF
[http://arxiv.org/pdf/1805.09028](http://arxiv.org/pdf/1805.09028)

