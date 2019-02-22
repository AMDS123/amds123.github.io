---
layout: post
title: "Domain Partitioning Network"
date: 2019-02-21 16:45:20
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Botos Csaba, Adnane Boukhayma, Viveka Kulharia, Andr&#xe1;s Horv&#xe1;th, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Standard adversarial training involves two agents, namely a generator and a discriminator, playing a mini-max game. However, even if the players converge to an equilibrium, the generator may only recover a part of the target data distribution, in a situation commonly referred to as mode collapse. In this work, we present the Domain Partitioning Network (DoPaNet), a new approach to deal with mode collapse in generative adversarial learning. We employ multiple discriminators, each encouraging the generator to cover a different part of the target distribution. To ensure these parts do not overlap and collapse into the same mode, we add a classifier as a third agent in the game. The classifier decides which discriminator the generator is trained against for each sample. Through experiments on toy examples and real images, we show the merits of DoPaNet in covering the real distribution and its superiority with respect to the competing methods. Besides, we also show that we can control the modes from which samples are generated using DoPaNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.08134](http://arxiv.org/abs/1902.08134)

##### PDF
[http://arxiv.org/pdf/1902.08134](http://arxiv.org/pdf/1902.08134)

