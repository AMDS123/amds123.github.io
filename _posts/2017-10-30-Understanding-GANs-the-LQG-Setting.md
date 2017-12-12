---
layout: post
title: "Understanding GANs: the LQG Setting"
date: 2017-10-30 07:20:35
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization
author: Soheil Feizi, Changho Suh, Fei Xia, David Tse
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) have become a popular method to learn a probability model from data. Many GAN architectures with different optimization metrics have been introduced recently. Instead of proposing yet another architecture, this paper aims to provide an understanding of some of the basic issues surrounding GANs. First, we propose a natural way of specifying the loss function for GANs by drawing a connection with supervised learning. Second, we shed light on the generalization peformance of GANs through the analysis of a simple LQG setting: the generator is Linear, the loss function is Quadratic and the data is drawn from a Gaussian distribution. We show that in this setting: 1) the optimal GAN solution converges to population Principal Component Analysis (PCA) as the number of training samples increases; 2) the number of samples required scales exponentially with the dimension of the data; 3) the number of samples scales almost linearly if the discriminator is constrained to be quadratic. Thus, linear generators and quadratic discriminators provide a good balance for fast learning.

##### Abstract (translated by Google)
生成对抗网络（GAN）已成为一种从数据中学习概率模型的流行方法。近来已经引入了许多具有不同优化度量的GAN体系结构。本文不是提出另一种架构，而是提供对GAN周围一些基本问题的理解。首先，我们提出一种通过与监督学习相联系来指定GAN的损失函数的自然方法。其次，我们通过分析一个简单的LQG设置，揭示了GAN的泛化性能：发生器是线性的，损失函数是二次的，数据是从高斯分布中得出的。我们表明，在这种情况下：1）当训练样本数量增加时，最优GAN解收敛于种群主成分分析（PCA） 2）所需样本的数量与数据的维数呈指数关系; 3）如果鉴别器被约束为二次的，则样本的数量几乎线性地缩放。因此，线性生成器和二次鉴别器为快速学习提供了一个很好的平衡点。

##### URL
[https://arxiv.org/abs/1710.10793](https://arxiv.org/abs/1710.10793)

##### PDF
[https://arxiv.org/pdf/1710.10793](https://arxiv.org/pdf/1710.10793)

