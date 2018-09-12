---
layout: post
title: "Unsupervised Cross-lingual Transfer of Word Embedding Spaces"
date: 2018-09-10 23:22:43
categories: arXiv_CL
tags: arXiv_CL Text_Classification Embedding Classification Prediction
author: Ruochen Xu, Yiming Yang, Naoki Otani, Yuexin Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Cross-lingual transfer of word embeddings aims to establish the semantic mappings among words in different languages by learning the transformation functions over the corresponding word embedding spaces. Successfully solving this problem would benefit many downstream tasks such as to translate text classification models from resource-rich languages (e.g. English) to low-resource languages. Supervised methods for this problem rely on the availability of cross-lingual supervision, either using parallel corpora or bilingual lexicons as the labeled data for training, which may not be available for many low resource languages. This paper proposes an unsupervised learning approach that does not require any cross-lingual labeled data. Given two monolingual word embedding spaces for any language pair, our algorithm optimizes the transformation functions in both directions simultaneously based on distributional matching as well as minimizing the back-translation losses. We use a neural network implementation to calculate the Sinkhorn distance, a well-defined distributional similarity measure, and optimize our objective through back-propagation. Our evaluation on benchmark datasets for bilingual lexicon induction and cross-lingual word similarity prediction shows stronger or competitive performance of the proposed method compared to other state-of-the-art supervised and unsupervised baseline methods over many language pairs.

##### Abstract (translated by Google)
单词嵌入的跨语言转移旨在通过学习相应单词嵌入空间上的变换函数来建立不同语言中单词之间的语义映射。成功解决这个问题将使许多下游任务受益，例如将文本分类模型从资源丰富的语言（例如英语）翻译成低资源语言。针对该问题的监督方法依赖于跨语言监督的可用性，使用并行语料库或双语词典作为用于训练的标记数据，这可能不适用于许多低资源语言。本文提出了一种无监督学习方法，不需要任何跨语言标记数据。给定两个单语单词嵌入空间用于任何语言对，我们的算法基于分布匹配同时优化两个方向上的变换函数以及最小化反向翻译损失。我们使用神经网络实现来计算Sinkhorn距离，一个明确定义的分布相似性度量，并通过反向传播优化我们的目标。我们对双语词典归纳和跨语言词汇相似性预测的基准数据集的评估显示，与其他最先进的监督和无监督基线方法相比，所提方法的性能更强或更具竞争性。

##### URL
[http://arxiv.org/abs/1809.03633](http://arxiv.org/abs/1809.03633)

##### PDF
[http://arxiv.org/pdf/1809.03633](http://arxiv.org/pdf/1809.03633)

