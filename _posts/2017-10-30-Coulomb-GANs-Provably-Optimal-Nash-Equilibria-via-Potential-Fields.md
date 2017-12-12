---
layout: post
title: "Coulomb GANs: Provably Optimal Nash Equilibria via Potential Fields"
date: 2017-10-30 09:43:53
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Thomas Unterthiner, Bernhard Nessler, Calvin Seward, Günter Klambauer, Martin Heusel, Hubert Ramsauer, Sepp Hochreiter
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) evolved into one of the most successful unsupervised techniques for generating realistic images. Even though it has recently been shown that GAN training converges, GAN models often end up in local Nash equilibria that are associated with mode collapse or otherwise fail to model the target distribution. We introduce Coulomb GANs, which pose the GAN learning problem as a potential field of charged particles, where generated samples are attracted to training set samples but repel each other. The discriminator learns a potential field while the generator decreases the energy by moving its samples along the vector (force) field determined by the gradient of the potential field. Through decreasing the energy, the GAN model learns to generate samples according to the whole target distribution and does not only cover some of its modes. We prove that Coulomb GANs possess only one Nash equilibrium which is optimal in the sense that the model distribution equals the target distribution. We show the efficacy of Coulomb GANs on a variety of image datasets. On LSUN and celebA, Coulomb GANs set a new state of the art and produce a previously unseen variety of different samples.

##### Abstract (translated by Google)
生成对抗网络（GAN）演变成用于生成逼真图像的最成功的无监督技术之一。尽管最近GAN训练收敛了，但是GAN模型经常以与模式崩溃相关的局部纳什均衡结束，或者不能模拟目标分布。我们引入库仑GAN，将GAN学习问题作为带电粒子的潜在领域，其中生成的样本被吸引到训练集样本，但相互排斥。鉴别器学习一个潜在的场，而发生器通过沿由势场的梯度确定的向量（力）场移动其样本来减少能量。通过降低能量，GAN模型学习根据整个目标分布生成样本，不仅覆盖了其中的一些模式。证明了库仑GAN只有一个纳什均衡，在模型分布等于目标分布的意义上是最优的。我们展示了库仑GAN在各种图像数据集上的功效。在LSUN和celebA，库仑GANs设置了一个新的艺术状态，并产生了以前看不到的各种样品。

##### URL
[https://arxiv.org/abs/1708.08819](https://arxiv.org/abs/1708.08819)

##### PDF
[https://arxiv.org/pdf/1708.08819](https://arxiv.org/pdf/1708.08819)

