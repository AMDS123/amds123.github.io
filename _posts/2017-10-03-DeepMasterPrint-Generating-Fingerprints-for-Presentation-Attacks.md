---
layout: post
title: "DeepMasterPrint: Generating Fingerprints for Presentation Attacks"
date: 2017-10-03 21:51:38
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization
author: Philip Bontrager, Aditi Roy, Julian Togelius, Nasir Memon
mathjax: true
---

* content
{:toc}

##### Abstract
We present two related methods for creating MasterPrints, synthetic fingerprints that are capable of spoofing multiple people's fingerprints. These methods achieve results that advance the state-of-the-art for single MasterPrint attack accuracy while being the first methods capable of creating MasterPrints at the image level. Both of the methods presented in this paper start with training a Generative Adversarial Network (GAN) on a set of real fingerprint images. The generator network is then used to search for fingerprints that maximize the probability of matching with most subjects in a dataset. The first method uses evolutionary search in the space of latent variables, and the second method uses gradient-based optimization. The unique combination of evolution and GANs is able to design a MasterPrint that a commercial fingerprint system matches to 23% of all users in a strict security setting, and 77% of all users at a looser security setting.

##### Abstract (translated by Google)
我们提出了两种创建MasterPrints的相关方法，即能够欺骗多个人的指纹的合成指纹。这些方法达到的结果是提高单个MasterPrint攻击精度的最新技术水平，同时也是第一个能够在图像级创建MasterPrints的方法。本文提出的两种方法都是从一组真实指纹图像上训练生成对抗网络（GAN）开始的。然后使用生成器网络来搜索指纹，该指纹最大化与数据集中的大多数主体匹配的概率。第一种方法是在潜变量的空间中使用进化搜索，第二种方法使用基于梯度的优化。进化和GAN独特的组合能够设计一个MasterPrint，一个商业指纹系统在严格的安全设置中与所有用户中的23％相匹配，77％的所有用户在较宽松的安全设置下。

##### URL
[https://arxiv.org/abs/1705.07386](https://arxiv.org/abs/1705.07386)

##### PDF
[https://arxiv.org/pdf/1705.07386](https://arxiv.org/pdf/1705.07386)

