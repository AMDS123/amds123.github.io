---
layout: post
title: "MMD GAN: Towards Deeper Understanding of Moment Matching Network"
date: 2017-11-27 14:04:35
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Gradient_Descent
author: Chun-Liang Li, Wei-Cheng Chang, Yu Cheng, Yiming Yang, Barnabás Póczos
mathjax: true
---

* content
{:toc}

##### Abstract
Generative moment matching network (GMMN) is a deep generative model that differs from Generative Adversarial Network (GAN) by replacing the discriminator in GAN with a two-sample test based on kernel maximum mean discrepancy (MMD). Although some theoretical guarantees of MMD have been studied, the empirical performance of GMMN is still not as competitive as that of GAN on challenging and large benchmark datasets. The computational efficiency of GMMN is also less desirable in comparison with GAN, partially due to its requirement for a rather large batch size during the training. In this paper, we propose to improve both the model expressiveness of GMMN and its computational efficiency by introducing adversarial kernel learning techniques, as the replacement of a fixed Gaussian kernel in the original GMMN. The new approach combines the key ideas in both GMMN and GAN, hence we name it MMD GAN. The new distance measure in MMD GAN is a meaningful loss that enjoys the advantage of weak topology and can be optimized via gradient descent with relatively small batch sizes. In our evaluation on multiple benchmark datasets, including MNIST, CIFAR- 10, CelebA and LSUN, the performance of MMD-GAN significantly outperforms GMMN, and is competitive with other representative GAN works.

##### Abstract (translated by Google)
生成矩匹配网络（GMMN）是一种深度生成模型，它不同于生成对手网络（GAN），用GAN中的鉴别器替换为基于核心最大均值差异（MMD）的双样本测试。虽然已经对MMD进行了一些理论上的研究，但GMMN的实证性能仍然不如GAN在挑战性和大型基准数据集上的竞争力。与GAN相比，GMMN的计算效率也不太理想，部分原因是在训练期间需要相当大的批量。在本文中，我们提出通过引入对抗核学习技术来提高GMMN的模型表达能力和计算效率，以替代原有GMMN中的固定高斯核。新方法结合了GMMN和GAN中的关键思想，因此我们将其命名为MMD GAN。 MMD GAN中的新距离度量是一个有意义的损失，它具有弱拓扑的优点，并且可以通过相对较小批量的梯度下降进行优化。在我们对包括MNIST，CIFAR-10，CelebA和LSUN在内的多个基准数据集的评估中，MMD-GAN的性能明显优于GMMN，并且与其他代表性的GAN作品相比具有竞争力。

##### URL
[https://arxiv.org/abs/1705.08584](https://arxiv.org/abs/1705.08584)

##### PDF
[https://arxiv.org/pdf/1705.08584](https://arxiv.org/pdf/1705.08584)

