---
layout: post
title: "Semi-Supervised Learning for Neural Machine Translation"
date: 2016-12-10 20:02:52
categories: arXiv_CL
tags: arXiv_CL NMT
author: Yong Cheng, Wei Xu, Zhongjun He, Wei He, Hua Wu, Maosong Sun, Yang Liu
mathjax: true
---

* content
{:toc}

##### Abstract
While end-to-end neural machine translation (NMT) has made remarkable progress recently, NMT systems only rely on parallel corpora for parameter estimation. Since parallel corpora are usually limited in quantity, quality, and coverage, especially for low-resource languages, it is appealing to exploit monolingual corpora to improve NMT. We propose a semi-supervised approach for training NMT models on the concatenation of labeled (parallel corpora) and unlabeled (monolingual corpora) data. The central idea is to reconstruct the monolingual corpora using an autoencoder, in which the source-to-target and target-to-source translation models serve as the encoder and decoder, respectively. Our approach can not only exploit the monolingual corpora of the target language, but also of the source language. Experiments on the Chinese-English dataset show that our approach achieves significant improvements over state-of-the-art SMT and NMT systems.

##### Abstract (translated by Google)
虽然端到端的神经机器翻译（NMT）近来取得了显着的进展，但NMT系统只依赖并行语料库进行参数估计。由于平行语料库在数量，质量和覆盖面方面通常有限，特别是对于低资源语言而言，利用单语语料库来提高NMT是有吸引力的。我们提出了一种半监督方法，用于在标注（平行语料库）和未标注（单语语料库）数据串联上训练NMT模型。其核心思想是利用自编码器重建单语言语料库，其中源到目标和目标到源翻译模型分别作为编码器和解码器。我们的方法不仅可以利用目标语言的单语语料，而且还可以利用源语言。对汉英数据集的实验表明，我们的方法比现有的SMT和NMT系统有显着的改进。

##### URL
[https://arxiv.org/abs/1606.04596](https://arxiv.org/abs/1606.04596)

