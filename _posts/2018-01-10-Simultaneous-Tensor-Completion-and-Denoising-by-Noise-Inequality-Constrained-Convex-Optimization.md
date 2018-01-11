---
layout: post
title: "Simultaneous Tensor Completion and Denoising by Noise Inequality Constrained Convex Optimization"
date: 2018-01-10 10:45:26
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization
author: Tatsuya Yokota, Hidekata Hontani
mathjax: true
---

* content
{:toc}

##### Abstract
Tensor completion is a technique of filling missing elements of the incomplete data tensors. It being actively studied based on the convex optimization scheme such as nuclear-norm minimization. When given data tensors include some noises, the nuclear-norm minimization problem is usually converted to the nuclear-norm `regularization' problem which simultaneously minimize penalty and error terms with some trade-off parameter. However, the good value of trade-off is not easily determined because of the difference of two units and the data dependence. In the sense of trade-off tuning, the noisy tensor completion problem with the `noise inequality constraint' is better choice than the `regularization' because the good noise threshold can be easily bounded with noise standard deviation. In this study, we tackle to solve the convex tensor completion problems with two types of noise inequality constraints: Gaussian and Laplace distributions. The contributions of this study are follows: (1) New tensor completion and denoising models using tensor total variation and nuclear-norm are proposed which can be characterized as a generalization/extension of many past matrix and tensor completion models, (2) proximal mappings for noise inequalities are derived which are analytically computable with low computational complexity, (3) convex optimization algorithm is proposed based on primal-dual splitting framework, (4) new step-size adaptation method is proposed to accelerate the optimization, and (5) extensive experiments demonstrated the advantages of the proposed method for visual data retrieval such as for color images, movies, and 3D-volumetric data.

##### Abstract (translated by Google)
张量完成是填充不完整数据张量的缺失元素的技术。正在积极研究基于核规范最小化等凸优化方案。当给定的数据张量包含一些噪声时，核范数最小化问题通常转化为核规范“正则化”问题，同时通过一些权衡参数来最小化惩罚和误差项。然而，由于两个单位的差异和数据的依赖性，折衷的价值并不容易确定。在折衷调整的意义上，噪声不等式约束下的噪声张量完成问题比“正则化”更好，因为好的噪声阈值可以容易地与噪声标准差有界。在本研究中，我们着手解决两类噪声不等式约束下的凸张量完成问题：高斯和拉普拉斯分布。本文的研究成果如下：（1）提出了张量全变差和核范数的新的张量完备和去噪模型，可以表征为许多过去的矩阵和张量完备模型的推广和推广，（2）近似映射（3）提出了基于原 - 双分裂框架的凸优化算法，（4）提出了新的步长自适应方法来加速优化，（5）广泛的实验证明了所提出的用于视觉数据检索的方法的优点，例如用于彩色图像，电影和3D体积数据。

##### URL
[https://arxiv.org/abs/1801.03299](https://arxiv.org/abs/1801.03299)

##### PDF
[https://arxiv.org/pdf/1801.03299](https://arxiv.org/pdf/1801.03299)

