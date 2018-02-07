---
layout: post
title: "Training Generative Adversarial Networks via Primal-Dual Subgradient Methods: A Lagrangian Perspective on GAN"
date: 2018-02-06 02:31:43
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization
author: Xu Chen, Jiang Wang, Hao Ge
mathjax: true
---

* content
{:toc}

##### Abstract
We relate the minimax game of generative adversarial networks (GANs) to finding the saddle points of the Lagrangian function for a convex optimization problem, where the discriminator outputs and the distribution of generator outputs play the roles of primal variables and dual variables, respectively. This formulation shows the connection between the standard GAN training process and the primal-dual subgradient methods for convex optimization. The inherent connection does not only provide a theoretical convergence proof for training GANs in the function space, but also inspires a novel objective function for training. The modified objective function forces the distribution of generator outputs to be updated along the direction according to the primal-dual subgradient methods. A toy example shows that the proposed method is able to resolve mode collapse, which in this case cannot be avoided by the standard GAN or Wasserstein GAN. Experiments on both Gaussian mixture synthetic data and real-world image datasets demonstrate the performance of the proposed method on generating diverse samples.

##### Abstract (translated by Google)
我们把生成对抗网络（GANs）的最小极小游戏与寻找凸优化问题的拉格朗日函数的鞍点相联系，其中鉴别器输出和生成器输出的分布分别扮演原始变量和对偶变量的角色。该公式表明标准GAN训练过程与凸二次梯度方法之间的联系。这种内在联系不仅为功能空间中的GANs训练提供了理论上的收敛性证明，而且为训练提供了新的目标函数。修正的目标函数迫使发电机输出的分布按照原始 - 对偶次梯度方法沿方向更新。一个玩具的例子表明，所提出的方法能够解决模式崩溃，在这种情况下，不能通过标准的GAN或Wasserstein GAN来避免。在高斯混合合成数据和真实世界的图像数据集上的实验证明了所提出的方法在产生不同样本上的性能。

##### URL
[https://arxiv.org/abs/1802.01765](https://arxiv.org/abs/1802.01765)

##### PDF
[https://arxiv.org/pdf/1802.01765](https://arxiv.org/pdf/1802.01765)

