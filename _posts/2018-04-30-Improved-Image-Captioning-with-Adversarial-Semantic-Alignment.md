---
layout: post
title: "Improved Image Captioning with Adversarial Semantic Alignment"
date: 2018-04-30 19:10:43
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial GAN Caption RNN Relation
author: Igor Melnyk, Tom Sercu, Pierre L. Dognin, Jarret Ross, Youssef Mroueh (IBM Research, USA)
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a new conditional GAN for image captioning that enforces semantic alignment between images and captions through a co-attentive discriminator and a context-aware LSTM sequence generator. In order to train these sequence GANs, we empirically study two algorithms: Self-critical Sequence Training (SCST) and Gumbel Straight-Through. Both techniques are confirmed to be viable for training sequence GANs. However, SCST displays better gradient behavior despite not directly leveraging gradients from the discriminator. This ensures a stronger stability of sequence GANs training and ultimately produces models with improved results under human evaluation. Automatic evaluation of GAN trained captioning models is an open question. To remedy this, we introduce a new semantic score with strong correlation to human judgement. As a paradigm for evaluation, we suggest that the generalization ability of the captioner to Out of Context (OOC) scenes is an important criterion to assess generalization and composition. To this end, we propose an OOC dataset which, combined with our automatic metric of semantic score, is a new benchmark for the captioning community to measure the generalization ability of automatic image captioning. Under this new OOC benchmark, and on the traditional MSCOCO dataset, our models trained with SCST have strong performance in both semantic score and human evaluation.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的条件GAN，用于图像字幕，通过共同注意的鉴别器和上下文感知LSTM序列生成器来强化图像和字幕之间的语义对齐。为了训练这些序列GANs，我们通过实证研究两种算法：自我关键序列训练（SCST）和Gumbel直通。这两种技术都被证实可用于训练序列GAN。然而，SCST显示出更好的梯度行为，尽管不直接利用鉴别器的梯度。这确保了序列GANs训练的更强稳定性并最终产生在人类评估下具有改进结果的模型。自动评估GAN训练的字幕模型是一个悬而未决的问题。为了解决这个问题，我们引入了一个与人类判断有很强相关性的新语义评分。作为一种评估范式，我们认为字幕对于语境外（OOC）场景的概括能力是评估概括和构图的重要标准。为此，我们提出了一个OOC数据集，结合我们的语义分数自动度量标准，为字幕社区测量自动图像字幕的泛化能力提供了新的基准。在这个新的OOC基准和传统的MSCOCO数据集中，我们使用SCST进行训练的模型在语义评分和人类评估方面都有很好的表现。

##### URL
[https://arxiv.org/abs/1805.00063](https://arxiv.org/abs/1805.00063)

##### PDF
[https://arxiv.org/pdf/1805.00063](https://arxiv.org/pdf/1805.00063)

