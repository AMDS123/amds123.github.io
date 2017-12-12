---
layout: post
title: "Softmax GAN"
date: 2017-04-20 15:35:14
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification
author: Min Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Softmax GAN is a novel variant of Generative Adversarial Network (GAN). The key idea of Softmax GAN is to replace the classification loss in the original GAN with a softmax cross-entropy loss in the sample space of one single batch. In the adversarial learning of $N$ real training samples and $M$ generated samples, the target of discriminator training is to distribute all the probability mass to the real samples, each with probability $\frac{1}{M}$, and distribute zero probability to generated data. In the generator training phase, the target is to assign equal probability to all data points in the batch, each with probability $\frac{1}{M+N}$. While the original GAN is closely related to Noise Contrastive Estimation (NCE), we show that Softmax GAN is the Importance Sampling version of GAN. We futher demonstrate with experiments that this simple change stabilizes GAN training.

##### Abstract (translated by Google)
Softmax GAN是Generative Adversarial Network（GAN）的新变种​​。 Softmax GAN的关键思想是用一个批次的样本空间中的softmax交叉熵损失替换原始GAN中的分类损失。在$ N $实训练样本和$ M $生成样本的敌对学习中，鉴别训练的目标是将所有的概率质量分配到实际样本，每个样本概率为$ \ frac {1} {M} $，向生成的数据分配零概率。在生成器训练阶段，目标是为批次中的所有数据点分配相等的概率，每个数据点的概率为$ \ frac {1} {M + N} $。原GAN与噪声对比估计（NCE）密切相关，我们发现Softmax GAN是GAN的重要抽样版本。我们进一步用实验证明这个简单的变化稳定了GAN训练。

##### URL
[https://arxiv.org/abs/1704.06191](https://arxiv.org/abs/1704.06191)

##### PDF
[https://arxiv.org/pdf/1704.06191](https://arxiv.org/pdf/1704.06191)

