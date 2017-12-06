---
layout: post
title: "An Empirical Analysis of NMT-Derived Interlingual Embeddings and their Use in Parallel Sentence Identification"
date: 2017-11-15 10:01:13
categories: arXiv_CL
tags: arXiv_CL NMT
author: Cristina España-Bonet, Ádám Csaba Varga, Alberto Barrón-Cedeño, Josef van Genabith
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end neural machine translation has overtaken statistical machine translation in terms of translation quality for some language pairs, specially those with large amounts of parallel data. Besides this palpable improvement, neural networks provide several new properties. A single system can be trained to translate between many languages at almost no additional cost other than training time. Furthermore, internal representations learned by the network serve as a new semantic representation of words -or sentences- which, unlike standard word embeddings, are learned in an essentially bilingual or even multilingual context. In view of these properties, the contribution of the present work is two-fold. First, we systematically study the NMT context vectors, i.e. output of the encoder, and their power as an interlingua representation of a sentence. We assess their quality and effectiveness by measuring similarities across translations, as well as semantically related and semantically unrelated sentence pairs. Second, as extrinsic evaluation of the first point, we identify parallel sentences in comparable corpora, obtaining an F1=98.2% on data from a shared task when using only NMT context vectors. Using context vectors jointly with similarity measures F1 reaches 98.9%.

##### Abstract (translated by Google)
端到端的神经机器翻译已经取代了某些语言对的翻译质量方面的统计机器翻译，特别是那些具有大量并行数据的翻译质量。除了这个明显的改进，神经网络提供了几个新的属性。一个系统可以训练翻译多种语言，几乎不需要额外的成本，除了训练时间。此外，网络学习到的内部表征可以作为一个新的语义表示 - 单词或句子 - 与标准词嵌入不同，它是以基本双语甚至多语言的语境学习的。鉴于这些性质，目前工作的贡献是双重的。首先，我们系统地研究NMT上下文向量，即编码器的输出，以及它们作为句子的句间表示的能力。我们通过测量翻译中的相似性，以及语义相关和语义上不相关的句子对来评估它们的质量和有效性。其次，作为第一点的外在评价，我们在可比较的语料库中识别平行句子，当仅使用NMT上下文向量时，从共享任务获得数据的F1 = 98.2％。使用上下文向量并结合相似性度量，F1达到98.9％。

##### URL
[https://arxiv.org/abs/1704.05415](https://arxiv.org/abs/1704.05415)

