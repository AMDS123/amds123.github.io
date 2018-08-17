---
layout: post
title: "Investigation of Using Disentangled and Interpretable Representations for One-shot Cross-lingual Voice Conversion"
date: 2018-08-15 22:21:42
categories: arXiv_SD
tags: arXiv_SD
author: Seyed Hamidreza Mohammadi, Taehwan Kim
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of cross-lingual voice conversion in non-parallel speech corpora and one-shot learning setting. Most prior work require either parallel speech corpora or enough amount of training data from a target speaker. However, we convert an arbitrary sentences of an arbitrary source speaker to target speaker's given only one target speaker training utterance. To achieve this, we formulate the problem as learning disentangled speaker-specific and context-specific representations and follow the idea of [1] which uses Factorized Hierarchical Variational Autoencoder (FHVAE). After training FHVAE on multi-speaker training data, given arbitrary source and target speakers' utterance, we estimate those latent representations and then reconstruct the desired utterance of converted voice to that of target speaker. We investigate the effectiveness of the approach by conducting voice conversion experiments with varying size of training utterances and it was able to achieve reasonable performance with even just one training utterance. We also examine the speech representation and show that World vocoder outperforms Short-time Fourier Transform (STFT) used in [1]. Finally, in the subjective tests, for one language and cross-lingual voice conversion, our approach achieved significantly better or comparable results compared to VAE-STFT and GMM baselines in speech quality and similarity.

##### Abstract (translated by Google)
我们研究了非平行语音语料库和一次性学习设置中的跨语音转换问题。大多数先前的工作需要并行语音语料库或来自目标说话者的足够量的训练数据。然而，我们将任意源说话者的任意句子转换为仅给出一个目标说话者训练话语的目标说话者。为了实现这一目标，我们将问题表述为学习解决说话者特定的和特定于上下文的表示，并遵循使用因式分层变分自动编码器（FHVAE）的[1]的思想。在对多个说话者训练数据进行FHVAE训练之后，给定任意源和目标说话者的话语，我们估计那些潜在的表示，然后将所需的转换语音的话语重建为目标说话者的话语。我们通过进行不同大小的训练话语的语音转换实验来研究该方法的有效性，并且即使只有一个训练话语也能够达到合理的性能。我们还研究了语音表示，并表明世界声码器的性能优于[1]中使用的短时傅立叶变换（STFT）。最后，在主观测试中，对于一种语言和跨语言语音转换，与语音质量和相似性中的VAE-STFT和GMM基线相比，我们的方法获得了显着更好或可比较的结果。

##### URL
[http://arxiv.org/abs/1808.05294](http://arxiv.org/abs/1808.05294)

##### PDF
[http://arxiv.org/pdf/1808.05294](http://arxiv.org/pdf/1808.05294)

