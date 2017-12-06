---
layout: post
title: 'Cache-based Document-level Neural Machine Translation'
date: 2017-11-30 04:30:53
categories: arXiv_CL
tags: arXiv_CL NMT
author: Shaohui Kuang, Deyi Xiong, Weihua Luo, Guodong Zhou
---

* content
{:toc}

##### Abstract
Sentences in a well-formed text are connected to each other via various links to form the cohesive structure of the text. Current neural machine translation (NMT) systems translate a text in a conventional sentence-by-sentence fashion, ignoring such cross-sentence links and dependencies. This may lead to generate an incohesive and incoherent target text for a cohesive and coherent source text. In order to handle this issue, we propose a cache-based approach to document-level neural machine translation by capturing contextual information either from recently translated sentences or the entire document. Particularly, we explore two types of caches: a dynamic cache, which stores words from the best translation hypotheses of preceding sentences, and a topic cache, which maintains a set of target-side topical words that are semantically related to the document to be translated. On this basis, we build a new layer to score target words in these two caches with a cache-based neural model. Here the estimated probabilities from the cache-based neural model are combined with NMT probabilities into the final word prediction probabilities via a gating mechanism. Finally, the proposed cache-based neural model is trained jointly with a state-of-the-art neural machine translation system in an end-to-end manner. On several NIST Chinese-English translation tasks, our experiments demonstrate that the proposed cache-based model achieves substantial improvements over several state-of-the-art SMT and NMT baselines.

##### Abstract (translated by Google)
一个格式正确的文本中的句子通过各种链接相互连接，形成文本的衔接结构。目前的神经机器翻译（NMT）系统以传统的逐句方式翻译文本，忽略这样的跨语句链接和依赖关系。这可能会导致一个连贯一致的源文本产生一个不连贯和不连贯的目标文本。为了解决这个问题，我们提出了一种基于缓存的文档级神经机器翻译方法，通过捕获最近翻译的句子或整个文档的上下文信息。特别地，我们探索了两种类型的高速缓存：动态高速缓存，其存储来自前面句子的最佳翻译假设的单词;以及主题高速缓存，其维护与要翻译的文档在语义上相关的一组目标侧主题词。在此基础上，利用基于缓存的神经模型，在这两个缓存中建立一个新层次来评分目标词。这里，基于缓存的神经模型的估计概率通过选通机制与NMT概率结合成最终的单词预测概率。最后，提出的基于缓存的神经模型与端到端的方式联合使用最先进的神经机器翻译系统进行训练。在NIST的几个中英文翻译任务中，我们的实验证明，所提出的基于缓存的模型比一些最先进的SMT和NMT基线实现了实质性的改进。

##### URL
[https://arxiv.org/abs/1711.11221](https://arxiv.org/abs/1711.11221)

