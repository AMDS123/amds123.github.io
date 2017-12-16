---
layout: post
title: "Deep Variational Inference Without Pixel-Wise Reconstruction"
date: 2016-11-16 10:20:10
categories: arXiv_CV
tags: arXiv_CV Inference
author: Siddharth Agrawal, Ambedkar Dukkipati
mathjax: true
---

* content
{:toc}

##### Abstract
Variational autoencoders (VAEs), that are built upon deep neural networks have emerged as popular generative models in computer vision. Most of the work towards improving variational autoencoders has focused mainly on making the approximations to the posterior flexible and accurate, leading to tremendous progress. However, there have been limited efforts to replace pixel-wise reconstruction, which have known shortcomings. In this work, we use real-valued non-volume preserving transformations (real NVP) to exactly compute the conditional likelihood of the data given the latent distribution. We show that a simple VAE with this form of reconstruction is competitive with complicated VAE structures, on image modeling tasks. As part of our model, we develop powerful conditional coupling layers that enable real NVP to learn with fewer intermediate layers.

##### Abstract (translated by Google)
基于深度神经网络的变分自动编码器（VAEs）已经成为计算机视觉领域的流行生成模型。大多数改进变分自动编码器的工作主要集中在使后验的近似方式灵活和准确，导致了巨大的进步。然而，取代已知缺点的像素重建的努力有限。在这项工作中，我们使用实值非容量保留变换（真正的NVP）精确计算给定潜在分布的数据的条件可能性。我们表明，一个简单的VAE与这种形式的重建是复杂的VAE结构，图像建模任务竞争力。作为我们模型的一部分，我们开发了强大的条件耦合层，使真正的NVP可以用更少的中间层进行学习。

##### URL
[https://arxiv.org/abs/1611.05209](https://arxiv.org/abs/1611.05209)

##### PDF
[https://arxiv.org/pdf/1611.05209](https://arxiv.org/pdf/1611.05209)

