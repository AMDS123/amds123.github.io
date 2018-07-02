---
layout: post
title: "CR-GAN: Learning Complete Representations for Multi-view Generation"
date: 2018-06-28 21:04:21
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Embedding
author: Yu Tian (1), Xi Peng (1), Long Zhao (1), Shaoting Zhang (2), Dimitris N. Metaxas (1) ((1) Rutgers University, (2) University of North Carolina at Charlotte)
mathjax: true
---

* content
{:toc}

##### Abstract
Generating multi-view images from a single-view input is an essential yet challenging problem. It has broad applications in vision, graphics, and robotics. Our study indicates that the widely-used generative adversarial network (GAN) may learn "incomplete" representations due to the single-pathway framework: an encoder-decoder network followed by a discriminator network. We propose CR-GAN to address this problem. In addition to the single reconstruction path, we introduce a generation sideway to maintain the completeness of the learned embedding space. The two learning pathways collaborate and compete in a parameter-sharing manner, yielding considerably improved generalization ability to "unseen" dataset. More importantly, the two-pathway framework makes it possible to combine both labeled and unlabeled data for self-supervised learning, which further enriches the embedding space for realistic generations. The experimental results prove that CR-GAN significantly outperforms state-of-the-art methods, especially when generating from "unseen" inputs in wild conditions.

##### Abstract (translated by Google)
从单视图输入生成多视图图像是一个基本而又具有挑战性的问题。它在视觉，图形和机器人领域具有广泛的应用。我们的研究表明，广泛使用的生成对抗网络（GAN）可能由于单路径框架而学习“不完整”表示：编码器 - 解码器网络，其后是鉴别器网络。我们提出CR-GAN来解决这个问题。除了单一的重建路径之外，我们还引入了一代代，以保持学习嵌入空间的完整性。这两种学习途径以参数共享的方式进行协作和竞争，从而大大提高了“看不见”数据集的泛化能力。更重要的是，双路径框架可以将标记和未标记数据结合起来进行自我监督学习，这进一步丰富了实际世代的嵌入空间。实验结果证明CR-GAN明显优于最先进的方法，特别是在野外条件下从“看不见的”输入产生时。

##### URL
[http://arxiv.org/abs/1806.11191](http://arxiv.org/abs/1806.11191)

##### PDF
[http://arxiv.org/pdf/1806.11191](http://arxiv.org/pdf/1806.11191)

