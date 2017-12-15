---
layout: post
title: "Compositional Sentence Representation from Character within Large Context Text"
date: 2016-06-03 13:35:17
categories: arXiv_CL
tags: arXiv_CL Embedding Optimization Classification Quantitative
author: Geonmin Kim, Hwaran Lee, Jisu Choi, Soo-young Lee
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a Hierarchical Composition Recurrent Network (HCRN) consisting of a 3-level hierarchy of compositional models: character, word and sentence. This model is designed to overcome two problems of representing a sentence on the basis of a constituent word sequence. The first is a data-sparsity problem in word embedding, and the other is a no usage of inter-sentence dependency. In the HCRN, word representations are built from characters, thus resolving the data-sparsity problem, and inter-sentence dependency is embedded into sentence representation at the level of sentence composition. We adopt a hierarchy-wise learning scheme in order to alleviate the optimization difficulties of learning deep hierarchical recurrent network in end-to-end fashion. The HCRN was quantitatively and qualitatively evaluated on a dialogue act classification task. Especially, sentence representations with an inter-sentence dependency are able to capture both implicit and explicit semantics of sentence, significantly improving performance. In the end, the HCRN achieved state-of-the-art performance with a test error rate of 22.7% for dialogue act classification on the SWBD-DAMSL database.

##### Abstract (translated by Google)
本文描述了一个分层组合复发网络（HCRN），由三层组成模型层次组成：字符，单词和句子。这个模型旨在克服两个基于组成单词序列表示句子的问题。首先是词嵌入中的数据稀疏性问题，另一个是不使用句间依赖关系。在HCRN中，文字表示是由字符构成的，从而解决了数据稀疏性问题，句子间的依存关系被嵌入到句子表达层面。我们采用层次式的学习方案，以缓解端到端学习深层次递归网络的优化难度。 HCRN在对话行为分类任务上进行了定量和定性评估。特别是，句子间依存关系的句子表征能够捕捉句子的隐式和显式语义，显着提高了表现。最后，HCRN在SWBD-DAMSL数据库的对话行为分类上达到了最高性能，测试错误率为22.7％。

##### URL
[https://arxiv.org/abs/1605.00482](https://arxiv.org/abs/1605.00482)

##### PDF
[https://arxiv.org/pdf/1605.00482](https://arxiv.org/pdf/1605.00482)

