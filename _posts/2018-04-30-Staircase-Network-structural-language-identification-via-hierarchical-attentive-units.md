---
layout: post
title: "Staircase Network: structural language identification via hierarchical attentive units"
date: 2018-04-30 07:55:55
categories: arXiv_AI
tags: arXiv_AI Classification Prediction Recognition
author: Trung Ngo Trong, Ville Hautamäki, Kristiina Jokinen
mathjax: true
---

* content
{:toc}

##### Abstract
Language recognition system is typically trained directly to optimize classification error on the target language labels, without using the external, or meta-information in the estimation of the model parameters. However labels are not independent of each other, there is a dependency enforced by, for example, the language family, which affects negatively on classification. The other external information sources (e.g. audio encoding, telephony or video speech) can also decrease classification accuracy. In this paper, we attempt to solve these issues by constructing a deep hierarchical neural network, where different levels of meta-information are encapsulated by attentive prediction units and also embedded into the training progress. The proposed method learns auxiliary tasks to obtain robust internal representation and to construct a variant of attentive units within the hierarchical model. The final result is the structural prediction of the target language and a closely related language family. The algorithm reflects a "staircase" way of learning in both its architecture and training, advancing from the fundamental audio encoding to the language family level and finally to the target language level. This process not only improves generalization but also tackles the issues of imbalanced class priors and channel variability in the deep neural network model. Our experimental findings show that the proposed architecture outperforms the state-of-the-art i-vector approaches on both small and big language corpora by a significant margin.

##### Abstract (translated by Google)
通常直接训练语言识别系统以优化目标语言标签上的分类错误，而无需在模型参数估计中使用外部或元信息。然而，标签并不相互独立，例如，语言系列会强制实施依赖性，这会对分类产生负面影响。其他外部信息源（例如音频编码，电话或视频语音）也会降低分类准确度。在本文中，我们试图通过构建一个深层次的神经网络来解决这些问题，其中不同层次的元信息被专注的预测单元封装并嵌入到训练进程中。所提出的方法学习辅助任务以获得强健的内部表示，并在分层模型内构建注意单元的变体。最终的结果是目标语言和密切相关的语言家族的结构预测。该算法反映了架构和训练的“阶梯”学习方式，从基础音频编码向语言家族层面发展，最终演变为目标语言层面。这个过程不仅提高了泛化能力，而且解决了深层神经网络模型中不平衡的类先验和信道变异问题。我们的实验结果表明，所提出的体系结构比小语言和大语言语料库中的最先进的i向量方法优越得多。

##### URL
[https://arxiv.org/abs/1804.11067](https://arxiv.org/abs/1804.11067)

##### PDF
[https://arxiv.org/pdf/1804.11067](https://arxiv.org/pdf/1804.11067)

