---
layout: post
title: "On Convergence and Stability of GANs"
date: 2017-12-10 15:24:13
categories: arXiv_CV
tags: arXiv_CV GAN
author: Naveen Kodali, Jacob Abernethy, James Hays, Zsolt Kira
mathjax: true
---

* content
{:toc}

##### Abstract
We propose studying GAN training dynamics as regret minimization, which is in contrast to the popular view that there is consistent minimization of a divergence between real and generated distributions. We analyze the convergence of GAN training from this new point of view to understand why mode collapse happens. We hypothesize the existence of undesirable local equilibria in this non-convex game to be responsible for mode collapse. We observe that these local equilibria often exhibit sharp gradients of the discriminator function around some real data points. We demonstrate that these degenerate local equilibria can be avoided with a gradient penalty scheme called DRAGAN. We show that DRAGAN enables faster training, achieves improved stability with fewer mode collapses, and leads to generator networks with better modeling performance across a variety of architectures and objective functions.

##### Abstract (translated by Google)
我们提出将GAN训练动力学作为遗憾最小化进行研究，这与普遍认为在实际分布和生成分布之间存在一致的最小化差异的观点相反。我们从这个新的角度分析了GAN训练的收敛性，以便理解模式崩溃发生的原因。我们假设在这个非凸面博弈中不希望的局部均衡的存在是造成模式崩溃的原因。我们观察到，这些局部均衡常常在一些实际数据点周围出现尖锐的鉴别函数梯度。我们证明这些退化的局部均衡可以用一个称为DRAGAN的梯度惩罚方案来避免。我们展示DRAGAN能够加快培训速度，以更少的模式崩溃实现更高的稳定性，并且可以在各种架构和目标功能上使生成器网络具有更好的建模性能。

##### URL
[http://arxiv.org/abs/1705.07215](http://arxiv.org/abs/1705.07215)

##### PDF
[http://arxiv.org/pdf/1705.07215](http://arxiv.org/pdf/1705.07215)

