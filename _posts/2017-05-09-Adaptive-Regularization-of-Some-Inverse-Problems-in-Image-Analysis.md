---
layout: post
title: "Adaptive Regularization of Some Inverse Problems in Image Analysis"
date: 2017-05-09 14:27:58
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Optimization Relation
author: Byung-Woo Hong, Ja-Keoung Koo, Martin Burger, Stefano Soatto
mathjax: true
---

* content
{:toc}

##### Abstract
We present an adaptive regularization scheme for optimizing composite energy functionals arising in image analysis problems. The scheme automatically trades off data fidelity and regularization depending on the current data fit during the iterative optimization, so that regularization is strongest initially, and wanes as data fidelity improves, with the weight of the regularizer being minimized at convergence. We also introduce the use of a Huber loss function in both data fidelity and regularization terms, and present an efficient convex optimization algorithm based on the alternating direction method of multipliers (ADMM) using the equivalent relation between the Huber function and the proximal operator of the one-norm. We illustrate and validate our adaptive Huber-Huber model on synthetic and real images in segmentation, motion estimation, and denoising problems.

##### Abstract (translated by Google)
我们提出了一个自适应正则化方案，用于优化图像分析问题中出现的复合能量泛函。该方案根据迭代优化过程中的当前数据拟合，自动将数据保真度和正则化进行折衷，使正则化效果最强，随着数据保真度的提高而减弱，正则化因子在收敛时权重最小。我们还介绍了在数据保真度和正则化项中使用Huber损失函数，并且利用Huber函数和近邻算子之间的等价关系，提出了一种基于乘法器交替方向法（ADMM）的高效凸优化算法。一个常态。我们说明和验证了我们的自适应Huber-Huber模型在合成和真实图像分割，运动估计和去噪问题。

##### URL
[https://arxiv.org/abs/1705.03350](https://arxiv.org/abs/1705.03350)

##### PDF
[https://arxiv.org/pdf/1705.03350](https://arxiv.org/pdf/1705.03350)

