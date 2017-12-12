---
layout: post
title: "Dualing GANs"
date: 2017-06-19 23:28:49
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Yujia Li, Alexander Schwing, Kuan-Chieh Wang, Richard Zemel
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial nets (GANs) are a promising technique for modeling a distribution from samples. It is however well known that GAN training suffers from instability due to the nature of its maximin formulation. In this paper, we explore ways to tackle the instability problem by dualizing the discriminator. We start from linear discriminators in which case conjugate duality provides a mechanism to reformulate the saddle point objective into a maximization problem, such that both the generator and the discriminator of this 'dualing GAN' act in concert. We then demonstrate how to extend this intuition to non-linear formulations. For GANs with linear discriminators our approach is able to remove the instability in training, while for GANs with nonlinear discriminators our approach provides an alternative to the commonly used GAN training algorithm.

##### Abstract (translated by Google)
生成对抗网络（GANs）是用于对来自样本的分布进行建模的有前途的技术。然而，众所周知GAN训练由于maximin公式的性质而受到不稳定的影响。在本文中，我们探索通过对鉴别器进行二元化来解决不稳定性问题的方法。我们从线性鉴别器开始，在这种情况下，共轭对偶提供了一个机制，将鞍点目标重新定义为一个最大化问题，使得这个“双重GAN”的发生器和鉴别器一致起作用。然后，我们演示如何将这种直觉扩展到非线性公式。对于具有线性鉴别器的GAN，我们的方法能够消除训练中的不稳定性，而对于具有非线性鉴别器的GAN，我们的方法提供了常用的GAN训练算法的替代方案。

##### URL
[https://arxiv.org/abs/1706.06216](https://arxiv.org/abs/1706.06216)

##### PDF
[https://arxiv.org/pdf/1706.06216](https://arxiv.org/pdf/1706.06216)

