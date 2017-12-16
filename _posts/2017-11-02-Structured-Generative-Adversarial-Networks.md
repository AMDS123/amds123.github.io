---
layout: post
title: "Structured Generative Adversarial Networks"
date: 2017-11-02 19:00:56
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Style_Transfer Image_Classification Classification
author: Zhijie Deng, Hao Zhang, Xiaodan Liang, Luona Yang, Shizhen Xu, Jun Zhu, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of conditional generative modeling based on designated semantics or structures. Existing models that build conditional generators either require massive labeled instances as supervision or are unable to accurately control the semantics of generated samples. We propose structured generative adversarial networks (SGANs) for semi-supervised conditional generative modeling. SGAN assumes the data x is generated conditioned on two independent latent variables: y that encodes the designated semantics, and z that contains other factors of variation. To ensure disentangled semantics in y and z, SGAN builds two collaborative games in the hidden space to minimize the reconstruction error of y and z, respectively. Training SGAN also involves solving two adversarial games that have their equilibrium concentrating at the true joint data distributions p(x, z) and p(x, y), avoiding distributing the probability mass diffusely over data space that MLE-based methods may suffer. We assess SGAN by evaluating its trained networks, and its performance on downstream tasks. We show that SGAN delivers a highly controllable generator, and disentangled representations; it also establishes start-of-the-art results across multiple datasets when applied for semi-supervised image classification (1.27%, 5.73%, 17.26% error rates on MNIST, SVHN and CIFAR-10 using 50, 1000 and 4000 labels, respectively). Benefiting from the separate modeling of y and z, SGAN can generate images with high visual quality and strictly following the designated semantic, and can be extended to a wide spectrum of applications, such as style transfer.

##### Abstract (translated by Google)
我们研究基于指定语义或结构的条件生成建模问题。构建条件生成器的现有模型要么需要大量标记的实例作为监督，要么无法准确地控制生成的样本的语义。我们提出了半监督条件生成建模的结构化生成对抗网络（SGAN）。 SGAN假定数据x是由两个独立的潜在变量生成的：y编码指定的语义，z包含其他变化因素。为了确保在y和z中的解构语义，SGAN在隐藏空间中构建两个协作游戏，以分别使y和z的重构误差最小化。训练SGAN还涉及解决两个对立的博弈，它们的均衡集中在真正的联合数据分布p（x，z）和p（x，y）上，避免在基于MLE的方法可能遭受的数据空间上分散弥散概率质量。我们通过评估其受训网络及其下游任务的表现评估SGAN。我们表明，SGAN提供了一个高度可控的生成器，并解开表示;当使用50,1000和4000个标签分别对MNIST，SVHN和CIFAR-10进行半监督图像分类（1.27％，5.73％，17.26％的误差率）时，它还建立了跨多个数据集的最先进的结果）。受益于y和z的单独建模，SGAN可以生成具有高视觉质量的图像，严格遵循指定的语义，并可扩展到样式转换等广泛的应用。

##### URL
[https://arxiv.org/abs/1711.00889](https://arxiv.org/abs/1711.00889)

##### PDF
[https://arxiv.org/pdf/1711.00889](https://arxiv.org/pdf/1711.00889)

