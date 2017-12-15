---
layout: post
title: "Joint Learning of the Embedding of Words and Entities for Named Entity Disambiguation"
date: 2016-06-10 01:51:26
categories: arXiv_SD
tags: arXiv_SD Knowledge Embedding
author: Ikuya Yamada, Hiroyuki Shindo, Hideaki Takeda, Yoshiyasu Takefuji
mathjax: true
---

* content
{:toc}

##### Abstract
Named Entity Disambiguation (NED) refers to the task of resolving multiple named entity mentions in a document to their correct references in a knowledge base (KB) (e.g., Wikipedia). In this paper, we propose a novel embedding method specifically designed for NED. The proposed method jointly maps words and entities into the same continuous vector space. We extend the skip-gram model by using two models. The KB graph model learns the relatedness of entities using the link structure of the KB, whereas the anchor context model aims to align vectors such that similar words and entities occur close to one another in the vector space by leveraging KB anchors and their context words. By combining contexts based on the proposed embedding with standard NED features, we achieved state-of-the-art accuracy of 93.1% on the standard CoNLL dataset and 85.2% on the TAC 2010 dataset.

##### Abstract (translated by Google)
命名实体消歧（NED）是指将文档中的多个命名实体提及解析为知识库（KB）（例如维基百科）中的正确引用的任务。在本文中，我们提出了一种专门为NED设计的新颖的嵌入方法。所提出的方法共同将单词和实体映射到相同的连续向量空间中。我们通过使用两个模型来扩展skip-gram模型。 KB图模型使用KB的链接结构来学习实体的相关性，而锚上下文模型旨在通过利用KB锚和它们的上下文词来对齐向量，使得相似的词和实体在向量空间中彼此接近地出现。通过将基于所提出的嵌入的上下文与标准NED特征相结合，我们在标准CoNLL数据集上获得了93.1％的最高精度，在TAC 2010数据集上达到了85.2％。

##### URL
[https://arxiv.org/abs/1601.01343](https://arxiv.org/abs/1601.01343)

##### PDF
[https://arxiv.org/pdf/1601.01343](https://arxiv.org/pdf/1601.01343)

