---
layout: post
title: "DualGAN: Unsupervised Dual Learning for Image-to-Image Translation"
date: 2017-08-09 06:43:40
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Zili Yi, Hao Zhang, Ping Tan, Minglun Gong
mathjax: true
---

* content
{:toc}

##### Abstract
Conditional Generative Adversarial Networks (GANs) for cross-domain image-to-image translation have made much progress recently. Depending on the task complexity, thousands to millions of labeled image pairs are needed to train a conditional GAN. However, human labeling is expensive, even impractical, and large quantities of data may not always be available. Inspired by dual learning from natural language translation, we develop a novel dual-GAN mechanism, which enables image translators to be trained from two sets of unlabeled images from two domains. In our architecture, the primal GAN learns to translate images from domain U to those in domain V, while the dual GAN learns to invert the task. The closed loop made by the primal and dual tasks allows images from either domain to be translated and then reconstructed. Hence a loss function that accounts for the reconstruction error of images can be used to train the translators. Experiments on multiple image translation tasks with unlabeled data show considerable performance gain of DualGAN over a single GAN. For some tasks, DualGAN can even achieve comparable or slightly better results than conditional GAN trained on fully labeled data.

##### Abstract (translated by Google)
用于跨域图像到图像转换的条件生成对抗网络（GAN）最近取得了很大的进展。根据任务的复杂性，需要数千到数百万个标记图像对来训练条件GAN。然而，人的标签是昂贵的，甚至是不切实际的，大量的数据可能并不总是可用的。受到自然语言翻译的双重学习的启发，我们开发了一种新型的双GAN机制，可以从两个领域的未标记图像中训练图像转换器。在我们的体系结构中，原始的GAN学习将图像从U域转换到V域的图像，而双GAN学习转换任务。由原始和双重任务所形成的闭环允许来自任一域的图像被翻译，然后重建。因此，可以利用一个解释图像重构误差的损失函数来训练翻译者。在没有标记数据的情况下对多个图像转换任务进行的实验显示在单个GAN上DualGAN性能有相当大的增益。对于一些任务，DualGAN甚至可以实现与完全标记的数据训练的条件GAN相比或稍微更好的结果。

##### URL
[https://arxiv.org/abs/1704.02510](https://arxiv.org/abs/1704.02510)

##### PDF
[https://arxiv.org/pdf/1704.02510](https://arxiv.org/pdf/1704.02510)

