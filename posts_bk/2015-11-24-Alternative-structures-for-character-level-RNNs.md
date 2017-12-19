---
layout: post
title: "Alternative structures for character-level RNNs"
date: 2015-11-24 17:35:35
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Piotr Bojanowski, Armand Joulin, Tomas Mikolov
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks are convenient and efficient models for language modeling. However, when applied on the level of characters instead of words, they suffer from several problems. In order to successfully model long-term dependencies, the hidden representation needs to be large. This in turn implies higher computational costs, which can become prohibitive in practice. We propose two alternative structural modifications to the classical RNN model. The first one consists on conditioning the character level representation on the previous word representation. The other one uses the character history to condition the output probability. We evaluate the performance of the two proposed modifications on challenging, multi-lingual real world data.

##### Abstract (translated by Google)
递归神经网络是用于语言建模的方便和有效的模型。然而，当应用在字符而不是文字层面时，他们遇到了几个问题。为了成功模拟长期依赖关系，隐藏表示需要很大。这反过来又意味着更高的计算成本，这在实践中可能变得不可行。我们对经典的RNN模型提出了两种替代的结构修改。第一个包括调节前一个单词表示的字符级别表示。另一个使用角色历史来调整输出概率。我们对具有挑战性的多语言现实世界数据提出的两项修改的性能进行评估。

##### URL
[https://arxiv.org/abs/1511.06303](https://arxiv.org/abs/1511.06303)

##### PDF
[https://arxiv.org/pdf/1511.06303](https://arxiv.org/pdf/1511.06303)

