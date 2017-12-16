---
layout: post
title: "HashGAN:Attention-aware Deep Adversarial Hashing for Cross Modal Retrieval"
date: 2017-11-26 08:14:13
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN
author: Xi Zhang, Siyu Zhou, Jiashi Feng, Hanjiang Lai, Bo Li, Yan Pan, Jian Yin, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
As the rapid growth of multi-modal data, hashing methods for cross-modal retrieval have received considerable attention. Deep-networks-based cross-modal hashing methods are appealing as they can integrate feature learning and hash coding into end-to-end trainable frameworks. However, it is still challenging to find content similarities between different modalities of data due to the heterogeneity gap. To further address this problem, we propose an adversarial hashing network with attention mechanism to enhance the measurement of content similarities by selectively focusing on informative parts of multi-modal data. The proposed new adversarial network, HashGAN, consists of three building blocks: 1) the feature learning module to obtain feature representations, 2) the generative attention module to generate an attention mask, which is used to obtain the attended (foreground) and the unattended (background) feature representations, 3) the discriminative hash coding module to learn hash functions that preserve the similarities between different modalities. In our framework, the generative module and the discriminative module are trained in an adversarial way: the generator is learned to make the discriminator cannot preserve the similarities of multi-modal data w.r.t. the background feature representations, while the discriminator aims to preserve the similarities of multi-modal data w.r.t. both the foreground and the background feature representations. Extensive evaluations on several benchmark datasets demonstrate that the proposed HashGAN brings substantial improvements over other state-of-the-art cross-modal hashing methods.

##### Abstract (translated by Google)
随着多模态数据的快速增长，跨模态检索的哈希方法受到了相当的关注。基于深度网络的交叉模式散列方法具有吸引力，因为它们可以将特征学习和散列编码整合到端到端的可训练框架中。然而，由于异质性差异，在不同的数据模式之间找到内容相似性仍然是一个挑战。为了进一步解决这个问题，我们提出了一个具有注意机制的对抗哈希网络，通过有选择性地关注多模态数据的信息部分来增强内容相似性的度量。提出的新的对抗网络HashGAN由三个构建块组成：1）获取特征表示的特征学习模块; 2）生成注意模块，用于生成注意模板，用于获得注意（前景）和无人注意（背景）特征表示，3）有差别的哈希编码模块，学习哈希函数，以保持不同模态之间的相似性。在我们的框架中，生成模块和判别模块是以对抗方式进行训练的：生成器被学习使得鉴别器不能保持多模式数据的相似性w.r.t.背景特征表示，而鉴别器的目的是保持多模态数据的相似性w.r.t.前景和背景特征表示。对几个基准数据集的广泛评估表明，所提出的HashGAN带来了实质性的改进，超过了其他最先进的跨模态哈希方法。

##### URL
[https://arxiv.org/abs/1711.09347](https://arxiv.org/abs/1711.09347)

##### PDF
[https://arxiv.org/pdf/1711.09347](https://arxiv.org/pdf/1711.09347)

