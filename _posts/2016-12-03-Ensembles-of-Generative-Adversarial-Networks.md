---
layout: post
title: "Ensembles of Generative Adversarial Networks"
date: 2016-12-03 17:49:02
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Yaxing Wang, Lichao Zhang, Joost van de Weijer
mathjax: true
---

* content
{:toc}

##### Abstract
Ensembles are a popular way to improve results of discriminative CNNs. The combination of several networks trained starting from different initializations improves results significantly. In this paper we investigate the usage of ensembles of GANs. The specific nature of GANs opens up several new ways to construct ensembles. The first one is based on the fact that in the minimax game which is played to optimize the GAN objective the generator network keeps on changing even after the network can be considered optimal. As such ensembles of GANs can be constructed based on the same network initialization but just taking models which have different amount of iterations. These so-called self ensembles are much faster to train than traditional ensembles. The second method, called cascade GANs, redirects part of the training data which is badly modeled by the first GAN to another GAN. In experiments on the CIFAR10 dataset we show that ensembles of GANs obtain model probability distributions which better model the data distribution. In addition, we show that these improved results can be obtained at little additional computational cost.

##### Abstract (translated by Google)
合奏是改善判别性CNN结果的流行方式。从不同初始化开始训练的多个网络的组合可显着改善结果。在本文中，我们调查了GANs集合的用法。 GAN的具体性质开辟了一些新的方法来建造乐团。第一个是基于这样一个事实，即在最优化GAN目标的最小极小游戏中，即使网络被认为是最优的，发电机网络也不断变化。因为这样的GAN集合可以基于相同的网络初始化而构建，而只是采用具有不同迭代量的模型。这些所谓的自我组合比传统乐队训练要快得多。第二种方法称为级联GAN，将由第一个GAN严重建模的部分训练数据重定向到另一个GAN。在CIFAR10数据集的实验中，我们发现GAN集合获得更好地模拟数据分布的模型概率分布。另外，我们表明，这些改进的结果可以在很少的附加计算成本下获得。

##### URL
[https://arxiv.org/abs/1612.00991](https://arxiv.org/abs/1612.00991)

##### PDF
[https://arxiv.org/pdf/1612.00991](https://arxiv.org/pdf/1612.00991)

