---
layout: post
title: "Dist-GAN: An Improved GAN using Distance Constraints"
date: 2018-07-27 08:04:52
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Ngoc-Trung Tran, Tuan-Anh Bui, Ngai-Man Cheung
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce effective training algorithms for Generative Adversarial Networks (GAN) to alleviate mode collapse and gradient vanishing. In our system, we constrain the generator by an Autoencoder (AE). We propose a formulation to consider the reconstructed samples from AE as "real" samples for the discriminator. This couples the convergence of the AE with that of the discriminator, effectively slowing down the convergence of discriminator and reducing gradient vanishing. Importantly, we propose two novel distance constraints to improve the generator. First, we propose a latent-data distance constraint to enforce compatibility between the latent sample distances and the corresponding data sample distances. We use this constraint to explicitly prevent the generator from mode collapse. Second, we propose a discriminator-score distance constraint to align the distribution of the generated samples with that of the real samples through the discriminator score. We use this constraint to guide the generator to synthesize samples that resemble the real ones. Our proposed GAN using these distance constraints, namely Dist-GAN, can achieve better results than state-of-the-art methods across benchmark datasets: synthetic, MNIST, MNIST-1K, CelebA, CIFAR-10 and STL-10 datasets. Our code is published here (https://github.com/tntrung/gan) for research.

##### Abstract (translated by Google)
我们为生成对抗网络（GAN）引入了有效的训练算法，以缓解模式崩溃和梯度消失。在我们的系统中，我们通过自动编码器（AE）约束发生器。我们提出了一种公式，将来自AE的重建样本视为鉴别器的“真实”样本。这将AE的收敛与鉴别器的收敛耦合，有效地减慢了鉴别器的收敛并减少了梯度消失。重要的是，我们提出了两种新的距离约束来改进发电机。首先，我们提出潜在数据距离约束，以强制潜在的样本距离和相应的数据样本距离之间的兼容性。我们使用此约束来明确地防止生成器模式崩溃。其次，我们提出了鉴别器 - 得分距离约束，以通过鉴别器得分将所生成的样本的分布与实际样本的分布对齐。我们使用此约束来指导生成器合成类似于真实样本的样本。我们提出的使用这些距离约束的GAN，即Dist-GAN，可以比基准数据集中的最先进方法获得更好的结果：合成，MNIST，MNIST-1K，CelebA，CIFAR-10和STL-10数据集。我们的代码发布在这里（https://github.com/tntrung/gan）用于研究。

##### URL
[http://arxiv.org/abs/1803.08887](http://arxiv.org/abs/1803.08887)

##### PDF
[http://arxiv.org/pdf/1803.08887](http://arxiv.org/pdf/1803.08887)

