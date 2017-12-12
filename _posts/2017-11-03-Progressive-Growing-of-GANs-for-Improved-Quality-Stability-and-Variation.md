---
layout: post
title: "Progressive Growing of GANs for Improved Quality, Stability, and Variation"
date: 2017-11-03 14:39:27
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Tero Karras, Timo Aila, Samuli Laine, Jaakko Lehtinen
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a new training methodology for generative adversarial networks. The key idea is to grow both the generator and discriminator progressively: starting from a low resolution, we add new layers that model increasingly fine details as training progresses. This both speeds the training up and greatly stabilizes it, allowing us to produce images of unprecedented quality, e.g., CelebA images at 1024^2. We also propose a simple way to increase the variation in generated images, and achieve a record inception score of 8.80 in unsupervised CIFAR10. Additionally, we describe several implementation details that are important for discouraging unhealthy competition between the generator and discriminator. Finally, we suggest a new metric for evaluating GAN results, both in terms of image quality and variation. As an additional contribution, we construct a higher-quality version of the CelebA dataset.

##### Abstract (translated by Google)
我们描述了一个新的生成敌对网络的培训方法。关键的思想是逐步发展生成器和鉴别器：从低分辨率开始，随着培训的进展，我们增加了新的层，可以模拟日益精细的细节。这既加快了训练速度，又极大地稳定了训练，使我们能够产生前所未有的质量图像，例如1024 ^ 2的CelebA图像。我们还提出了一种简单的方法来增加生成图像的变化，并在无监督的CIFAR10中实现了8.80的记录启动得分。此外，我们描述了几个实施细节，这对于阻止发生器和鉴别器之间的不健康竞争是重要的。最后，我们提出了一个评估GAN结果的新指标，无论是在图像质量还是变化方面。作为额外的贡献，我们构建了CelebA数据集的更高质量的版本。

##### URL
[https://arxiv.org/abs/1710.10196](https://arxiv.org/abs/1710.10196)

##### PDF
[https://arxiv.org/pdf/1710.10196](https://arxiv.org/pdf/1710.10196)

