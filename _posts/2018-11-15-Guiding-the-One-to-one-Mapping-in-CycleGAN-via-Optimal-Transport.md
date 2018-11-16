---
layout: post
title: "Guiding the One-to-one Mapping in CycleGAN via Optimal Transport"
date: 2018-11-15 10:34:33
categories: arXiv_AI
tags: arXiv_AI GAN
author: Guansong Lu, Zhiming Zhou, Yuxuan Song, Kan Ren, Yong Yu
mathjax: true
---

* content
{:toc}

##### Abstract
CycleGAN is capable of learning a one-to-one mapping between two data distributions without paired examples, achieving the task of unsupervised data translation. However, there is no theoretical guarantee on the property of the learned one-to-one mapping in CycleGAN. In this paper, we experimentally find that, under some circumstances, the one-to-one mapping learned by CycleGAN is just a random one within the large feasible solution space. Based on this observation, we explore to add extra constraints such that the one-to-one mapping is controllable and satisfies more properties related to specific tasks. We propose to solve an optimal transport mapping restrained by a task-specific cost function that reflects the desired properties, and use the barycenters of optimal transport mapping to serve as references for CycleGAN. Our experiments indicate that the proposed algorithm is capable of learning a one-to-one mapping with the desired properties.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06284](http://arxiv.org/abs/1811.06284)

##### PDF
[http://arxiv.org/pdf/1811.06284](http://arxiv.org/pdf/1811.06284)

