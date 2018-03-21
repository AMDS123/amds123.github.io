---
layout: post
title: "A Hierarchical Latent Vector Model for Learning Long-Term Structure in Music"
date: 2018-03-13 21:14:46
categories: arXiv_SD
tags: arXiv_SD Embedding
author: Adam Roberts, Jesse Engel, Colin Raffel, Curtis Hawthorne, Douglas Eck
mathjax: true
---

* content
{:toc}

##### Abstract
The Variational Autoencoder (VAE) has proven to be an effective model for producing semantically meaningful latent representations for natural data. However, it has thus far seen limited application to sequential data, and, as we demonstrate, existing recurrent VAE models have difficulty modeling sequences with long-term structure. To address this issue, we propose the use of a hierarchical decoder, which first outputs embeddings for subsequences of the input and then uses these embeddings to generate each subsequence independently. This structure encourages the model to utilize its latent code, thereby avoiding the "posterior collapse" problem which remains an issue for recurrent VAEs. We apply this architecture to modeling sequences of musical notes and find that it exhibits dramatically better sampling, interpolation, and reconstruction performance than a "flat" baseline model. An implementation of our "MusicVAE" is available online at this http URL

##### Abstract (translated by Google)
变分自动编码器（VAE）已被证明是为自然数据生成语义上有意义的潜在表示的有效模型。然而，迄今为止，它对顺序数据的应用有限，而且，正如我们所证明的那样，现有的经常性VAE模型难以对具有长期结构的序列进行建模。为了解决这个问题，我们建议使用分层解码器，它首先输出输入的子序列的嵌入，然后使用这些嵌入来独立地生成每个子序列。这种结构鼓励模型利用其潜在的代码，从而避免了“后期崩溃”问题，这仍然是复发性VAE的问题。我们将这种体系结构应用于对音符进行建模序列，发现它比“平坦”基线模型显示出更好的采样，插值和重构性能。我们的“MusicVAE”的实现可通过此http URL在线获得

##### URL
[https://arxiv.org/abs/1803.05428](https://arxiv.org/abs/1803.05428)

##### PDF
[https://arxiv.org/pdf/1803.05428](https://arxiv.org/pdf/1803.05428)

