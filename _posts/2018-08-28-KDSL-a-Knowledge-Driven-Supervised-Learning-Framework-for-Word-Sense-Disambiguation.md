---
layout: post
title: "KDSL: a Knowledge-Driven Supervised Learning Framework for Word Sense Disambiguation"
date: 2018-08-28 12:20:37
categories: arXiv_AI
tags: arXiv_AI Knowledge Relation
author: Shi Yin, Yi Zhou, Chengguang Li, Shangfei Wang, Jianmin Ji, Xiaoping Chen, Ruili Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose KDSL, a new word sense disambiguation (WSD) framework that utilizes knowledge to automatically generate sense-labeled data for supervised learning. First, from WordNet, we au- tomatically construct a semantic knowledge base called DisDict, which provides refined feature words that highlight the differences among word senses, i.e., synsets. Second, we automatically generate new sense-labeled data by DisDict from unlabeled corpora. Third, these generated data, together with manually labeled data, are fed to a supervised learning neural network to model the semantic relations among synsets, feature words and their contexts. Jointly with the supervised learning process, we also implement unsupervised learning on unlabeled data as an auxiliary task. The experimental results show that KDSL outperforms several representative state-of-the-art methods on various major benchmarks. Interestingly, it performs relatively well even when manually labeled data is unavailable, thus provides a new promising backoff strategy for WSD.

##### Abstract (translated by Google)
我们提出KDSL，一种新的词义消歧（WSD）框架，利用知识自动生成用于监督学习的感知标记数据。首先，从WordNet，我们自动构建一个名为DisDict的语义知识库，它提供了精确的特征词，突出了词义之间的差异，即同义词。其次，我们通过DisDict从未标记的语料库中自动生成新的带有感知标记的数据。第三，将这些生成的数据与手动标记的数据一起馈送到监督学习神经网络，以模拟同义词，特征词及其上下文之间的语义关系。与监督学习过程相结合，我们还对无标签数据实施无监督学习作为辅助任务。实验结果表明，KDSL在各种主要基准测试中优于几种具有代表性的最先进方法。有趣的是，即使手动标记的数据不可用，它也表现得相对较好，从而为WSD提供了一种新的有希望的退避策略。

##### URL
[http://arxiv.org/abs/1808.09888](http://arxiv.org/abs/1808.09888)

##### PDF
[http://arxiv.org/pdf/1808.09888](http://arxiv.org/pdf/1808.09888)

