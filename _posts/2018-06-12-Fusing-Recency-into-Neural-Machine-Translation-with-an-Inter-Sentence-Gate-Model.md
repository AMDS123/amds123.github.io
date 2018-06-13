---
layout: post
title: "Fusing Recency into Neural Machine Translation with an Inter-Sentence Gate Model"
date: 2018-06-12 12:37:20
categories: arXiv_CL
tags: arXiv_CL NMT
author: Shaohui Kuang, Deyi Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) systems are usually trained on a large amount of bilingual sentence pairs and translate one sentence at a time, ignoring inter-sentence information. This may make the translation of a sentence ambiguous or even inconsistent with the translations of neighboring sentences. In order to handle this issue, we propose an inter-sentence gate model that uses the same encoder to encode two adjacent sentences and controls the amount of information flowing from the preceding sentence to the translation of the current sentence with an inter-sentence gate. In this way, our proposed model can capture the connection between sentences and fuse recency from neighboring sentences into neural machine translation. On several NIST Chinese-English translation tasks, our experiments demonstrate that the proposed inter-sentence gate model achieves substantial improvements over the baseline.

##### Abstract (translated by Google)
神经机器翻译（NMT）系统通常训练大量的双语句对，并且一次翻译一个句子，而忽略句间信息。这可能会使句子的翻译模糊或甚至与相邻句子的翻译不一致。为了解决这个问题，我们提出了一个句间间门模型，它使用相同的编码器对两个相邻的句子进行编码，并控制从前一个句子到当前句子翻译的信息量。通过这种方式，我们提出的模型可以捕捉句子之间的连接，并将邻近句子中的新近度融合为神经机器翻译。在几个NIST中英文翻译任务中，我们的实验表明，提出的句间内门模型比基线实现了实质性的改进。

##### URL
[http://arxiv.org/abs/1806.04466](http://arxiv.org/abs/1806.04466)

##### PDF
[http://arxiv.org/pdf/1806.04466](http://arxiv.org/pdf/1806.04466)

