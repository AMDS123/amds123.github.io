---
layout: post
title: "A segmental framework for fully-unsupervised large-vocabulary speech recognition"
date: 2017-09-16 09:36:02
categories: arXiv_CL
tags: arXiv_CL Knowledge Segmentation Speech_Recognition Embedding Language_Model Recognition
author: Herman Kamper, Aren Jansen, Sharon Goldwater
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-resource speech technology is a growing research area that aims to develop methods for speech processing in the absence of transcriptions, lexicons, or language modelling text. Early term discovery systems focused on identifying isolated recurring patterns in a corpus, while more recent full-coverage systems attempt to completely segment and cluster the audio into word-like units---effectively performing unsupervised speech recognition. This article presents the first attempt we are aware of to apply such a system to large-vocabulary multi-speaker data. Our system uses a Bayesian modelling framework with segmental word representations: each word segment is represented as a fixed-dimensional acoustic embedding obtained by mapping the sequence of feature frames to a single embedding vector. We compare our system on English and Xitsonga datasets to state-of-the-art baselines, using a variety of measures including word error rate (obtained by mapping the unsupervised output to ground truth transcriptions). Very high word error rates are reported---in the order of 70--80% for speaker-dependent and 80--95% for speaker-independent systems---highlighting the difficulty of this task. Nevertheless, in terms of cluster quality and word segmentation metrics, we show that by imposing a consistent top-down segmentation while also using bottom-up knowledge from detected syllable boundaries, both single-speaker and multi-speaker versions of our system outperform a purely bottom-up single-speaker syllable-based approach. We also show that the discovered clusters can be made less speaker- and gender-specific by using an unsupervised autoencoder-like feature extractor to learn better frame-level features (prior to embedding). Our system's discovered clusters are still less pure than those of unsupervised term discovery systems, but provide far greater coverage.

##### Abstract (translated by Google)
零资源语音技术是一个正在成长的研究领域，其目标是在没有抄录，词典或语言建模文本的情况下开发语音处理方法。早期的发现系统侧重于识别语料库中孤立的重复发生的模式，而更近期的全覆盖系统试图将音频完全分段并聚类成类似单词的单元 - 有效地执行无监督语音识别。本文介绍了我们应用这种系统应用于大词汇量多语音数据的第一次尝试。我们的系统使用具有分词表示的贝叶斯建模框架：每个分词表示为通过将特征帧序列映射到单个嵌入向量而获得的固定声学嵌入。我们使用包括字错误率（通过将无监督输出映射到地面实况转录获得）在内的各种措施，将我们的英语和西森加数据集系统与最先进的基线进行比较。报告了很高的字错误率 - 依赖于讲话者的系数为70-80％，独立于讲话者的系统为80-95％ - 强调了这项任务的难度。然而，就集群质量和分词度量而言，我们表明，通过施加一致的自顶向下分割，同时还使用从检测到的音节边界的自下而上的知识，我们的系统的单扬声器和多扬声器版本都纯粹地自下而上的单扬声器基于音节的方法。我们还表明，通过使用无监督的类似自动编码器的特征提取器来学习更好的帧级特征（在嵌入之前），发现的聚类可以减少说话者和性别特定性。我们的系统发现的集群仍然不如非监督式的发现系统纯粹，但提供更大的覆盖范围。

##### URL
[https://arxiv.org/abs/1606.06950](https://arxiv.org/abs/1606.06950)

##### PDF
[https://arxiv.org/pdf/1606.06950](https://arxiv.org/pdf/1606.06950)

