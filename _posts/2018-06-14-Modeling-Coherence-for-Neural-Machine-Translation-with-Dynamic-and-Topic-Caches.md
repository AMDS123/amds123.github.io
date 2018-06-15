---
layout: post
title: "Modeling Coherence for Neural Machine Translation with Dynamic and Topic Caches"
date: 2018-06-14 09:25:29
categories: arXiv_CL
tags: arXiv_CL NMT Prediction
author: Shaohui Kuang, Deyi Xiong, Weihua Luo, Guodong Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Sentences in a well-formed text are connected to each other via various links to form the cohesive structure of the text. Current neural machine translation (NMT) systems translate a text in a conventional sentence-by-sentence fashion, ignoring such cross-sentence links and dependencies. This may lead to generate an incoherent target text for a coherent source text. In order to handle this issue, we propose a cache-based approach to modeling coherence for neural machine translation by capturing contextual information either from recently translated sentences or the entire document. Particularly, we explore two types of caches: a dynamic cache, which stores words from the best translation hypotheses of preceding sentences, and a topic cache, which maintains a set of target-side topical words that are semantically related to the document to be translated. On this basis, we build a new layer to score target words in these two caches with a cache-based neural model. Here the estimated probabilities from the cache-based neural model are combined with NMT probabilities into the final word prediction probabilities via a gating mechanism. Finally, the proposed cache-based neural model is trained jointly with NMT system in an end-to-end manner. Experiments and analysis presented in this paper demonstrate that the proposed cache-based model achieves substantial improvements over several state-of-the-art SMT and NMT baselines.

##### Abstract (translated by Google)
正确形式的文本中的句子通过各种链接相互连接，形成文本的内聚结构。目前的神经机器翻译（NMT）系统以传统的逐句方式翻译文本，忽略了这种跨语句链接和依赖关系。这可能会导致为连贯的源文本生成不连贯的目标文本。为了解决这个问题，我们提出了一种基于缓存的方法，通过从最近翻译的句子或整个文档中捕获上下文信息来建立神经机器翻译的一致性。特别是，我们探索了两种类型的缓存：一个动态缓存，它存储来自前面句子最佳翻译假设的单词;以及一个主题缓存，它维护一组与目标文本语义相关的目标端主题词。在此基础上，我们构建了一个新层，通过基于缓存的神经模型对这两个缓存中的目标词进行评分。这里，来自基于缓存的神经模型的估计概率通过选通机制与NMT概率结合成最终的单词预测概率。最后，所提出的基于缓存的神经模型以端到端的方式与NMT系统联合训练。本文提供的实验和分析表明，所提出的基于缓存的模型相对于几个最先进的SMT和NMT基线实现了实质性改进。

##### URL
[http://arxiv.org/abs/1711.11221](http://arxiv.org/abs/1711.11221)

##### PDF
[http://arxiv.org/pdf/1711.11221](http://arxiv.org/pdf/1711.11221)

