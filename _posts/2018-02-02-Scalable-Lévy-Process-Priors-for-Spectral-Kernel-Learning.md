---
layout: post
title: "Scalable Lévy Process Priors for Spectral Kernel Learning"
date: 2018-02-02 01:40:46
categories: arXiv_AI
tags: arXiv_AI Regularization Prediction
author: Phillip A. Jang, Andrew E. Loeb, Matthew B. Davidow, Andrew Gordon Wilson
mathjax: true
---

* content
{:toc}

##### Abstract
Gaussian processes are rich distributions over functions, with generalization properties determined by a kernel function. When used for long-range extrapolation, predictions are particularly sensitive to the choice of kernel parameters. It is therefore critical to account for kernel uncertainty in our predictive distributions. We propose a distribution over kernels formed by modelling a spectral mixture density with a L\'evy process. The resulting distribution has support for all stationary covariances--including the popular RBF, periodic, and Mat\'ern kernels--combined with inductive biases which enable automatic and data efficient learning, long-range extrapolation, and state of the art predictive performance. The proposed model also presents an approach to spectral regularization, as the L\'evy process introduces a sparsity-inducing prior over mixture components, allowing automatic selection over model order and pruning of extraneous components. We exploit the algebraic structure of the proposed process for $\mathcal{O}(n)$ training and $\mathcal{O}(1)$ predictions. We perform extrapolations having reasonable uncertainty estimates on several benchmarks, show that the proposed model can recover flexible ground truth covariances and that it is robust to errors in initialization.

##### Abstract (translated by Google)
高斯过程是丰富的函数分布，泛化属性由内核函数决定。当用于远程外推时，预测对内核参数的选择特别敏感。因此，在我们的预测分布中考虑内核不确定性至关重要。我们提出了一个核心分布形成了一个光谱混合密度与一个L evy过程建模。由此产生的分布支持所有固定的协方差 - 包括流行的RBF，周期性和Mat \'ern内核 - 结合感应偏差，使得自动和数据有效的学习，远程外推和最先进的预测性能。所提出的模型也提出了一种光谱正则化的方法，因为L \ evy过程在混合分量上引入了先验稀疏，允许在模型阶数上自动选择和修剪无关分量。我们利用$ \ mathcal {O}（n）$训练和$ \ mathcal {O}（1）$预测的建议过程的代数结构。我们在几个基准上进行具有合理的不确定性估计的外推，表明所提出的模型能够恢复灵活的地面真值协方差，并且对初始化中的误差具有鲁棒性。

##### URL
[https://arxiv.org/abs/1802.00530](https://arxiv.org/abs/1802.00530)

##### PDF
[https://arxiv.org/pdf/1802.00530](https://arxiv.org/pdf/1802.00530)

