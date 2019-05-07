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


##### URL
[https://arxiv.org/abs/1705.07215](https://arxiv.org/abs/1705.07215)

##### PDF
[https://arxiv.org/pdf/1705.07215](https://arxiv.org/pdf/1705.07215)

