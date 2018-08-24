---
layout: post
title: "DOPING: Generative Data Augmentation for Unsupervised Anomaly Detection with GAN"
date: 2018-08-23 04:44:25
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Detection
author: Swee Kiat Lim, Yi Loo, Ngoc-Trung Tran, Ngai-Man Cheung, Gemma Roig, Yuval Elovici
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, the introduction of the generative adversarial network (GAN) and its variants has enabled the generation of realistic synthetic samples, which has been used for enlarging training sets. Previous work primarily focused on data augmentation for semi-supervised and supervised tasks. In this paper, we instead focus on unsupervised anomaly detection and propose a novel generative data augmentation framework optimized for this task. In particular, we propose to oversample infrequent normal samples - normal samples that occur with small probability, e.g., rare normal events. We show that these samples are responsible for false positives in anomaly detection. However, oversampling of infrequent normal samples is challenging for real-world high-dimensional data with multimodal distributions. To address this challenge, we propose to use a GAN variant known as the adversarial autoencoder (AAE) to transform the high-dimensional multimodal data distributions into low-dimensional unimodal latent distributions with well-defined tail probability. Then, we systematically oversample at the `edge' of the latent distributions to increase the density of infrequent normal samples. We show that our oversampling pipeline is a unified one: it is generally applicable to datasets with different complex data distributions.

##### Abstract (translated by Google)
最近，生成对抗网络（GAN）及其变体的引入使得能够生成逼真的合成样本，其已经用于扩大训练集。以前的工作主要集中在半监督和监督任务的数据增加上。在本文中，我们将重点放在无监督异常检测上，并提出一种针对此任务优化的新型生成数据增强框架。特别地，我们建议对不频繁的正常样本进行过采样 - 以小概率发生的正常样本，例如罕见的正常事件。我们证明这些样本是异常检测中误报的原因。然而，对于具有多峰分布的真实世界高维数据，不频繁的正常样本的过采样是具有挑战性的。为了解决这一挑战，我们建议使用称为对抗性自动编码器（AAE）的GAN变体将高维多模态数据分布转换为具有明确定义的尾概率的低维单峰潜在分布。然后，我们系统地对潜在分布的“边缘”进行过采样，以增加不常见的正常样本的密度。我们表明我们的过采样管道是统一的：它通常适用于具有不同复杂数据分布的数据集。

##### URL
[https://arxiv.org/abs/1808.07632](https://arxiv.org/abs/1808.07632)

##### PDF
[https://arxiv.org/pdf/1808.07632](https://arxiv.org/pdf/1808.07632)

