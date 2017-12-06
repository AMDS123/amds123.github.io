---
layout: post
title: "Unsupervised Neural Machine Translation"
date: 2017-10-30 16:17:34
categories: arXiv_CL
tags: arXiv_CL NMT
author: Mikel Artetxe, Gorka Labaka, Eneko Agirre, Kyunghyun Cho
mathjax: true
---

* content
{:toc}

##### Abstract
In spite of the recent success of neural machine translation (NMT) in standard benchmarks, the lack of large parallel corpora poses a major practical problem for many language pairs. There have been several proposals to alleviate this issue with, for instance, triangulation and semi-supervised learning techniques, but they still require a strong cross-lingual signal. In this work, we completely remove the need of parallel data and propose a novel method to train an NMT system in a completely unsupervised manner, relying on nothing but monolingual corpora. Our model builds upon the recent work on unsupervised embedding mappings, and consists of a slightly modified attentional encoder-decoder model that can be trained on monolingual corpora alone using a combination of denoising and backtranslation. Despite the simplicity of the approach, our system obtains 15.56 and 10.21 BLEU points in WMT 2014 French-to-English and German-to-English translation. The model can also profit from small parallel corpora, and attains 21.81 and 15.24 points when combined with 100,000 parallel sentences, respectively. Our approach is a breakthrough in unsupervised NMT, and opens exciting opportunities for future research.

##### Abstract (translated by Google)
尽管最近在标准基准测试中神经机器翻译（NMT）已经取得了成功，但缺乏大的平行语料对于许多语言对来说是一个重大的实际问题。例如三角测量和半监督学习技术已经有几个建议来缓解这个问题，但是它们仍然需要强大的跨语言信号。在这项工作中，我们完全消除了对并行数据的需求，并提出了一种新的方法来训练一个完全无监督的NMT系统，只依靠单语语料库。我们的模型建立在最近关于无监督嵌入映射的工作上，并且包括稍微改进的注意编码器 - 解码器模型，其可以单独使用去噪和回传的组合在单语语料上训练。尽管方法简单，但我们的系统在WMT 2014法语对英语和德语对英语的翻译中获得15.56和10.21 BLEU分。该模型也可以从小平行语料库中获益，分别结合100,000个平行句子得到21.81和15.24分。我们的方法是无监督NMT的一个突破，并为未来的研究开辟了令人振奋的机会。

##### URL
[https://arxiv.org/abs/1710.11041](https://arxiv.org/abs/1710.11041)

