---
layout: post
title: "Multilingual Extractive Reading Comprehension by Runtime Machine Translation"
date: 2018-09-10 12:41:21
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Akari Asai, Akiko Eriguchi, Kazuma Hashimoto, Yoshimasa Tsuruoka
mathjax: true
---

* content
{:toc}

##### Abstract
Existing end-to-end neural network models for extractive Reading Comprehension (RC) have enjoyed the benefit of a large amount of hand-annotated training data. However, such a dataset is usually available only in English, which limits one from building an extractive RC model for a language of interest. In this paper, we introduce the first extractive RC systems for non-English languages without using language-specific RC training data, but instead by using an English RC model and an attention-based Neural Machine Translation (NMT) model. To train the NMT model for specific language directions, we take advantage of constantly growing web resources to automatically construct parallel corpora, rather than assuming the availability of high quality parallel corpora of the target domain. Our method first translates a paragraph-question pair into English so that the English extractive RC model can output its answer. The attention mechanism in the NMT model is further used to directly align the answer in the target text of interest. Experimental results in two non-English languages, namely Japanese and French, show that our method significantly outperforms a back-translation baseline of a state-of-the-art product-level machine translation system. Moreover, our ablation studies suggest that adding a small number of manually translated questions, besides an automatically created corpus, could further improve the performance of the extractive RC systems for non-English languages.

##### Abstract (translated by Google)
用于提取阅读理解（RC）的现有端到端神经网络模型已经享受了大量手工注释的训练数据的益处。然而，这样的数据集通常仅以英语提供，这限制了为感兴趣的语言构建提取RC模型。在本文中，我们介绍了非英语语言的第一个提取RC系统，而不使用特定于语言的RC训练数据，而是使用英语RC模型和基于注意力的神经机器翻译（NMT）模型。为了针对特定语言方向训练NMT模型，我们利用不断增长的Web资源来自动构建并行语料库，而不是假设目标域的高质量并行语料库的可用性。我们的方法首先将段落 - 问题对翻译成英语，以便英语提取RC模型可以输出其答案。 NMT模型中的注意机制进一步用于直接对齐目标文本中的答案。两种非英语语言（即日语和法语）的实验结果表明，我们的方法明显优于最先进的产品级机器翻译系统的反向翻译基线。此外，我们的消融研究表明，除了自动创建的语料库之外，添加少量手动翻译的问题可以进一步提高非英语语言的提取RC系统的性能。

##### URL
[http://arxiv.org/abs/1809.03275](http://arxiv.org/abs/1809.03275)

##### PDF
[http://arxiv.org/pdf/1809.03275](http://arxiv.org/pdf/1809.03275)

