---
layout: post
title: "Low-Rank Hidden State Embeddings for Viterbi Sequence Labeling"
date: 2017-08-02 00:05:10
categories: arXiv_CL
tags: arXiv_CL Embedding Inference RNN Recognition
author: Dung Thai, Shikhar Murty, Trapit Bansal, Luke Vilnis, David Belanger, Andrew McCallum
mathjax: true
---

* content
{:toc}

##### Abstract
In textual information extraction and other sequence labeling tasks it is now common to use recurrent neural networks (such as LSTM) to form rich embedded representations of long-term input co-occurrence patterns. Representation of output co-occurrence patterns is typically limited to a hand-designed graphical model, such as a linear-chain CRF representing short-term Markov dependencies among successive labels. This paper presents a method that learns embedded representations of latent output structure in sequence data. Our model takes the form of a finite-state machine with a large number of latent states per label (a latent variable CRF), where the state-transition matrix is factorized---effectively forming an embedded representation of state-transitions capable of enforcing long-term label dependencies, while supporting exact Viterbi inference over output labels. We demonstrate accuracy improvements and interpretable latent structure in a synthetic but complex task based on CoNLL named entity recognition.

##### Abstract (translated by Google)
在文本信息提取和其他序列标记任务中，现在通常使用递归神经网络（例如LSTM）来形成长期输入共现模式的丰富的嵌入表示。输出共现模式的表示通常限于手工设计的图形模型，例如代表连续标签之间的短期马尔可夫相关性的线性链CRF。本文提出了一种在序列数据中学习潜在输出结构的嵌入表示的方法。我们的模型采用有限状态机的形式，每个标签具有大量的潜在状态（一个潜在变量CRF），状态转换矩阵被分解了 - 有效地形成了一个能够执行的状态转换的嵌入表示长期标签依赖性，同时支持输出标签上的精确维特比推断。我们演示准确性改进和可解释的潜在结构在合成但复杂的任务基于CoNLL命名实体识别。

##### URL
[https://arxiv.org/abs/1708.00553](https://arxiv.org/abs/1708.00553)

##### PDF
[https://arxiv.org/pdf/1708.00553](https://arxiv.org/pdf/1708.00553)

