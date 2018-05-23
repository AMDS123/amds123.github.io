---
layout: post
title: "Generative timbre spaces with variational audio synthesis"
date: 2018-05-22 11:05:46
categories: arXiv_SD
tags: arXiv_SD Regularization GAN Relation
author: Philippe Esling, Axel Chemla--Romeu-Santos, Adrien Bitton
mathjax: true
---

* content
{:toc}

##### Abstract
Timbre spaces have been used in music perception to study the relationships between instruments based on dissimilarity ratings. However, these spaces do not generalize, need to be reconstructed for each novel example and are not continuous, preventing audio synthesis. In parallel, generative models have aimed to provide methods for synthesizing novel timbres. However, these systems do not provide an explicit control structure, nor do they provide an understanding of their inner workings and are not related to any perceptually relevant information. Here, we show that Variational Auto-Encoders (VAE) can alleviate these limitations by constructing generative timbre spaces. To do so, we adapt VAEs to create a generative latent space, while using perceptual ratings from timbre studies to regularize the organization of this space. The resulting space allows to analyze novel instruments, while being able to synthesize audio from any point of this space. We introduce a specific regularization allowing to directly enforce given similarity ratings onto these spaces. We compare the resulting space to existing timbre spaces and show that they provide almost similar distance relationships. We evaluate several spectral transforms and show that the Non-Stationary Gabor Transform (NSGT) provides the highest correlation to timbre spaces and the best quality of synthesis. We show that these spaces can generalize to novel instruments and can generate any path between instruments to understand their timbre relationships. As these spaces are continuous, we study how the traditional acoustic descriptors behave along the latent dimensions. We show that descriptors have an overall non-linear topology, but follow a locally smooth evolution. Based on this, we introduce a method for descriptor-based synthesis and show that we can control the descriptors of an instrument while keeping its timbre structure.

##### Abstract (translated by Google)
音乐空间已被用于音乐感知，以研究基于不相似性评级的乐器之间的关系。然而，这些空间并没有概括，需要为每个新颖的例子重新构建，并且不是连续的，以防止音频合成。同时，生成模型旨在提供合成新颖音色的方法。然而，这些系统不提供明确的控制结构，也不提供对其内部工作的理解，也不涉及任何感知相关的信息。在这里，我们展示变分自动编码器（VAE）可以通过构建生成音色空间来缓解这些限制。为此，我们调整VAE以创造一个生成的潜在空间，同时使用音色研究的感性评分来规范这个空间的组织。由此产生的空间允许分析新颖的乐器，同时能够从该空间的任何点合成音频。我们介绍一种特定的正则化，允许直接在这些空间上执行给定的相似度评定。我们将产生的空间与现有的音色空间进行比较，并显示它们提供了几乎相似的距离关系。我们评估了几种光谱变换，并表明非平稳Gabor变换（NSGT）提供了最高的音色空间相关性和最佳的合成质量。我们表明，这些空间可以推广到新颖的乐器，并可以在乐器之间生成任何路径以了解他们的音色关系。由于这些空间是连续的，所以我们研究传统声学描述符如何沿着潜在维度行为。我们显示描述符具有整体非线性拓扑，但遵循本地平滑演进。在此基础上，我们介绍一种基于描述符的合成方法，并表明我们可以在保持音色结构的同时控制乐器的描述符。

##### URL
[https://arxiv.org/abs/1805.08501](https://arxiv.org/abs/1805.08501)

##### PDF
[https://arxiv.org/pdf/1805.08501](https://arxiv.org/pdf/1805.08501)

