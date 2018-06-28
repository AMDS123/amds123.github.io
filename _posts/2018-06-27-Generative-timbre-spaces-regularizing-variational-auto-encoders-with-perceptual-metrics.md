---
layout: post
title: "Generative timbre spaces: regularizing variational auto-encoders with perceptual metrics"
date: 2018-06-27 12:33:45
categories: arXiv_SD
tags: arXiv_SD Regularization GAN Relation
author: Philippe Esling, Axel Chemla--Romeu-Santos, Adrien Bitton
mathjax: true
---

* content
{:toc}

##### Abstract
Timbre spaces have been used in music perception to study the perceptual relationships between instruments based on dissimilarity ratings. However, these spaces do not generalize to novel examples and do not provide an invertible mapping, preventing audio synthesis. In parallel, generative models have aimed to provide methods for synthesizing novel timbres. However, these systems do not provide an understanding of their inner workings and are usually not related to any perceptually relevant information. Here, we show that Variational Auto-Encoders (VAE) can alleviate all of these limitations by constructing generative timbre spaces. To do so, we adapt VAEs to learn an audio latent space, while using perceptual ratings from timbre studies to regularize the organization of this space. The resulting space allows us to analyze novel instruments, while being able to synthesize audio from any point of this space. We introduce a specific regularization allowing to enforce any given similarity distances onto these spaces. We show that the resulting space provide almost similar distance relationships as timbre spaces. We evaluate several spectral transforms and show that the Non-Stationary Gabor Transform (NSGT) provides the highest correlation to timbre spaces and the best quality of synthesis. Furthermore, we show that these spaces can generalize to novel instruments and can generate any path between instruments to understand their timbre relationships. As these spaces are continuous, we study how audio descriptors behave along the latent dimensions. We show that even though descriptors have an overall non-linear topology, they follow a locally smooth evolution. Based on this, we introduce a method for descriptor-based synthesis and show that we can control the descriptors of an instrument while keeping its timbre structure.

##### Abstract (translated by Google)
音乐空间已被用于音乐感知，以研究基于差异评级的乐器之间的感知关系。然而，这些空间不能推广到新颖的例子，也不提供可逆映射，从而阻止音频合成。同时，生成模型旨在提供合成新颖音色的方法。然而，这些系统并不能提供对其内部工作的理解，并且通常与任何感知相关的信息无关。在这里，我们展示变分自动编码器（VAE）可以通过构建生成音色空间来缓解所有这些限制。为此，我们调整VAE以学习音频潜在空间，同时利用音色研究的感知评分来规范这个空间的组织。由此产生的空间使我们能够分析新颖的乐器，同时能够从这个空间的任何点合成音频。我们介绍一种特定的正则化，允许在这些空间上强制任何给定的相似距离。我们表明，由此产生的空间提供了几乎与音色空间类似的距离关系。我们评估了几种光谱变换，并表明非平稳Gabor变换（NSGT）提供了最高的音色空间相关性和最佳的合成质量。此外，我们表明，这些空间可以推广到新颖的乐器，并可以产生乐器之间的任何路径，以了解他们的音色关系。由于这些空间是连续的，我们研究音频描述符如何沿着潜在维度行为。我们表明即使描述符具有整体非线性拓扑，它们也遵循本地平滑演进。在此基础上，我们介绍一种基于描述符的合成方法，并表明我们可以在保持音色结构的同时控制乐器的描述符。

##### URL
[http://arxiv.org/abs/1805.08501](http://arxiv.org/abs/1805.08501)

##### PDF
[http://arxiv.org/pdf/1805.08501](http://arxiv.org/pdf/1805.08501)

