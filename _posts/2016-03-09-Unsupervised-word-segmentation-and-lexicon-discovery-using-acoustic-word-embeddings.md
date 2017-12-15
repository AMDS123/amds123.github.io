---
layout: post
title: "Unsupervised word segmentation and lexicon discovery using acoustic word embeddings"
date: 2016-03-09 11:14:23
categories: arXiv_SD
tags: arXiv_SD Segmentation Face Embedding Language_Model Recognition
author: Herman Kamper, Aren Jansen, Sharon Goldwater
mathjax: true
---

* content
{:toc}

##### Abstract
In settings where only unlabelled speech data is available, speech technology needs to be developed without transcriptions, pronunciation dictionaries, or language modelling text. A similar problem is faced when modelling infant language acquisition. In these cases, categorical linguistic structure needs to be discovered directly from speech audio. We present a novel unsupervised Bayesian model that segments unlabelled speech and clusters the segments into hypothesized word groupings. The result is a complete unsupervised tokenization of the input speech in terms of discovered word types. In our approach, a potential word segment (of arbitrary length) is embedded in a fixed-dimensional acoustic vector space. The model, implemented as a Gibbs sampler, then builds a whole-word acoustic model in this space while jointly performing segmentation. We report word error rates in a small-vocabulary connected digit recognition task by mapping the unsupervised decoded output to ground truth transcriptions. The model achieves around 20% error rate, outperforming a previous HMM-based system by about 10% absolute. Moreover, in contrast to the baseline, our model does not require a pre-specified vocabulary size.

##### Abstract (translated by Google)
在只有未标记的语音数据可用的设置中，语音技术需要在没有转录，发音词典或语言建模文本的情况下开发。婴儿语言习得模式面临类似的问题。在这些情况下，分类语言结构需要直接从语音音频中发现。我们提出了一种新的无监督贝叶斯模型，分割未标记的语音，并将这些分段聚类成虚拟的词组。结果是根据发现的词类型对输入语音进行完全的无监督分词。在我们的方法中，一个潜在的（任意长度的）字段被嵌入到一个固定的声学向量空间中。该模型被实现为一个Gibbs采样器，然后在这个空间中建立一个全字的声学模型，同时执行分割。我们通过将无监督的解码输出映射到地面实况转录来报告小词汇连接的数字识别任务中的词错误率。该模型达到了20％左右的错误率，比以前的基于HMM的系统的绝对值​​大约高出10％。而且，与基线相比，我们的模型不需要预先指定的词汇大小。

##### URL
[https://arxiv.org/abs/1603.02845](https://arxiv.org/abs/1603.02845)

##### PDF
[https://arxiv.org/pdf/1603.02845](https://arxiv.org/pdf/1603.02845)

