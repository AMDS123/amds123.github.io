---
layout: post
title: "Multi-Modal Mean-Fields via Cardinality-Based Clamping"
date: 2016-11-23 19:14:25
categories: arXiv_CV
tags: arXiv_CV Inference
author: Pierre Baqué, François Fleuret, Pascal Fua
mathjax: true
---

* content
{:toc}

##### Abstract
Mean Field inference is central to statistical physics. It has attracted much interest in the Computer Vision community to efficiently solve problems expressible in terms of large Conditional Random Fields. However, since it models the posterior probability distribution as a product of marginal probabilities, it may fail to properly account for important dependencies between variables. We therefore replace the fully factorized distribution of Mean Field by a weighted mixture of such distributions, that similarly minimizes the KL-Divergence to the true posterior. By introducing two new ideas, namely, conditioning on groups of variables instead of single ones and using a parameter of the conditional random field potentials, that we identify to the temperature in the sense of statistical physics to select such groups, we can perform this minimization efficiently. Our extension of the clamping method proposed in previous works allows us to both produce a more descriptive approximation of the true posterior and, inspired by the diverse MAP paradigms, fit a mixture of Mean Field approximations. We demonstrate that this positively impacts real-world algorithms that initially relied on mean fields.

##### Abstract (translated by Google)
平均场推断是统计物理的核心。它已经引起了计算机视觉社区的很大兴趣，以有效地解决大条件随机场可表达的问题。但是，由于它将后验概率分布建模为边际概率的乘积，因此可能无法正确解释变量之间的重要依赖关系。因此，我们用这种分布的加权混合来代替均值场的完全因式分布，同样地将KL分离最小化到真正的后验。通过引入两个新的思想，即调节变量组而不是单个变量，并使用条件随机场势的参数，我们从统计物理意义上确定温度来选择这些组，我们可以执行这个最小化有效率的。我们在前面的工作中提出的钳制方法的扩展使我们能够产生对真实后验的更加描述性的近似，并且受不同的MAP范例的启发，拟合了平均场近似的混合。我们证明这对最初依赖平均场的真实世界算法产生了积极的影响。

##### URL
[https://arxiv.org/abs/1611.07941](https://arxiv.org/abs/1611.07941)

##### PDF
[https://arxiv.org/pdf/1611.07941](https://arxiv.org/pdf/1611.07941)

