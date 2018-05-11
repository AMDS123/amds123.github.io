---
layout: post
title: "Improving GAN Training via Binarized Representation Entropy Regularization"
date: 2018-05-09 06:31:24
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN Classification
author: Yanshuai Cao, Gavin Weiguang Ding, Kry Yik-Chau Lui, Ruitong Huang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel regularizer to improve the training of Generative Adversarial Networks (GANs). The motivation is that when the discriminator D spreads out its model capacity in the right way, the learning signals given to the generator G are more informative and diverse. These in turn help G to explore better and discover the real data manifold while avoiding large unstable jumps due to the erroneous extrapolation made by D. Our regularizer guides the rectifier discriminator D to better allocate its model capacity, by encouraging the binary activation patterns on selected internal layers of D to have a high joint entropy. Experimental results on both synthetic data and real datasets demonstrate improvements in stability and convergence speed of the GAN training, as well as higher sample quality. The approach also leads to higher classification accuracies in semi-supervised learning.

##### Abstract (translated by Google)
我们提出了一种新型正规化器来改善生成敌对网络（GAN）的训练。其动机是，当鉴别器D以正确的方式扩展其模型容量时，给予发生器G的学习信号更具信息性和多样性。这些帮助G更好地探索和发现真正的数据流形，同时避免由于D引起的错误外推导致的大幅不稳定跳跃。我们的正则化器通过鼓励选定的二元激活模式来引导整流器鉴别器D更好地分配其模型能力D的内部层具有较高的联合熵。综合数据和真实数据集的实验结果证明了GAN训练的稳定性和收敛速度的改善，以及更高的样本质量。该方法还导致半监督学习中更高的分类精度。

##### URL
[https://arxiv.org/abs/1805.03644](https://arxiv.org/abs/1805.03644)

##### PDF
[https://arxiv.org/pdf/1805.03644](https://arxiv.org/pdf/1805.03644)

