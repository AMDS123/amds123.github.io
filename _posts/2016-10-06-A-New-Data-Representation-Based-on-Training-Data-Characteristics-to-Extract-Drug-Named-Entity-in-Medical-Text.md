---
layout: post
title: "A New Data Representation Based on Training Data Characteristics to Extract Drug Named-Entity in Medical Text"
date: 2016-10-06 14:38:09
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding RNN Recognition
author: Sadikin Mujiono, Mohamad Ivan Fanany, Chan Basaruddin
mathjax: true
---

* content
{:toc}

##### Abstract
One essential task in information extraction from the medical corpus is drug name recognition. Compared with text sources come from other domains, the medical text is special and has unique characteristics. In addition, the medical text mining poses more challenges, e.g., more unstructured text, the fast growing of new terms addition, a wide range of name variation for the same drug. The mining is even more challenging due to the lack of labeled dataset sources and external knowledge, as well as multiple token representations for a single drug name that is more common in the real application setting. Although many approaches have been proposed to overwhelm the task, some problems remained with poor F-score performance (less than 0.75). This paper presents a new treatment in data representation techniques to overcome some of those challenges. We propose three data representation techniques based on the characteristics of word distribution and word similarities as a result of word embedding training. The first technique is evaluated with the standard NN model, i.e., MLP (Multi-Layer Perceptrons). The second technique involves two deep network classifiers, i.e., DBN (Deep Belief Networks), and SAE (Stacked Denoising Encoders). The third technique represents the sentence as a sequence that is evaluated with a recurrent NN model, i.e., LSTM (Long Short Term Memory). In extracting the drug name entities, the third technique gives the best F-score performance compared to the state of the art, with its average F-score being 0.8645.

##### Abstract (translated by Google)
从医学语料库提取信息的一个重要任务是药物名称识别。与其他领域的文本来源相比，医学文本特殊，具有独特的特点。另外，医学文本挖掘带来了更多的挑战，例如，更多的非结构化文本，新术语增加的快速增长，同一药物的广泛名称变化。由于缺乏标记的数据集来源和外部知识，以及在实际应用环境中更常见的单一药物名称的多个标记表示，挖掘更具挑战性。尽管已经提出了许多方法来压倒任务，但是F评分表现差（0.75以下）仍然存在一些问题。本文提出了一种新的数据表示技术，以克服其中的一些挑战。根据词嵌入训练的结果，提出了基于词分布特征和词相似性的三种数据表示技术。第一种技术是使用标准NN模型，即MLP（多层感知器）来评估的。第二种技术涉及两个深度网络分类器，即DBN（Deep Belief Networks）和SAE（Stacked Denoising Encoders）。第三种技术将句子表示为用循环的NN模型，即LSTM（长期短期记忆）评估的序列。在提取药物名称实体方面，与现有技术相比，第三种技术提供了最佳的F-score性能，其平均F-分数为0.8645。

##### URL
[https://arxiv.org/abs/1610.01891](https://arxiv.org/abs/1610.01891)

##### PDF
[https://arxiv.org/pdf/1610.01891](https://arxiv.org/pdf/1610.01891)

