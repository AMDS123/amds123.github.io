---
layout: post
title: "Self-Supervised GAN to Counter Forgetting"
date: 2018-10-27 04:49:25
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification
author: Ting Chen, Xiaohua Zhai, Neil Houlsby
mathjax: true
---

* content
{:toc}

##### Abstract
GANs involve training two networks in an adversarial game, where each network's task depends on its adversary. Recently, several works have framed GAN training as an online or continual learning problem. We focus on the discriminator, which must perform classification under an (adversarially) shifting data distribution. When trained on sequential tasks, neural networks exhibit \emph{forgetting}. For GANs, discriminator forgetting leads to training instability. To counter forgetting, we encourage the discriminator to maintain useful representations by adding a self-supervision. Conditional GANs have a similar effect using labels. However, our self-supervised GAN does not require labels, and closes the performance gap between conditional and unconditional models. We show that, in doing so, the self-supervised discriminator learns better representations than regular GANs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11598](http://arxiv.org/abs/1810.11598)

##### PDF
[http://arxiv.org/pdf/1810.11598](http://arxiv.org/pdf/1810.11598)

