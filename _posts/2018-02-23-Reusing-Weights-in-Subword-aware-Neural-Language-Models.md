---
layout: post
title: "Reusing Weights in Subword-aware Neural Language Models"
date: 2018-02-23 03:44:15
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model
author: Zhenisbek Assylbekov, Rustem Takhanov
mathjax: true
---

* content
{:toc}

##### Abstract
We propose several ways of reusing subword embeddings and other weights in subword-aware neural language models. The proposed techniques do not benefit a competitive character-aware model, but some of them improve the performance of syllable- and morpheme-aware models while showing significant reductions in model sizes. We discover a simple hands-on principle: in a multi-layer input embedding model, layers should be tied consecutively bottom-up if reused at output. Our best morpheme-aware model with properly reused weights beats the competitive word-level model by a large margin across multiple languages and has 20%-87% fewer parameters.

##### Abstract (translated by Google)
我们提出了几种方法在子词感知神经语言模型中重用子词嵌入和其他权重。所提出的技术不利于竞争性的字符意识模型，但其中一些提高了音节和语素感知模型的性能，同时显示模型大小的显着减小。我们发现了一个简单的动手原理：在多层输入嵌入模型中，如果输出重用，层应该从下至上连续地连接。我们最好的词素感知模型具有适当重复使用的权重，在多种语言中大幅度地跳过了竞争性词级模型，参数数量减少了20％-87％。

##### URL
[https://arxiv.org/abs/1802.08375](https://arxiv.org/abs/1802.08375)

##### PDF
[https://arxiv.org/pdf/1802.08375](https://arxiv.org/pdf/1802.08375)

