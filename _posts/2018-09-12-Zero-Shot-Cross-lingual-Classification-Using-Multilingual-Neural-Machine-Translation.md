---
layout: post
title: "Zero-Shot Cross-lingual Classification Using Multilingual Neural Machine Translation"
date: 2018-09-12 21:34:03
categories: arXiv_AI
tags: arXiv_AI Review Attention Transfer_Learning NMT Classification
author: Akiko Eriguchi, Melvin Johnson, Orhan Firat, Hideto Kazawa, Wolfgang Macherey
mathjax: true
---

* content
{:toc}

##### Abstract
Transferring representations from large supervised tasks to downstream tasks has shown promising results in AI fields such as Computer Vision and Natural Language Processing (NLP). In parallel, the recent progress in Machine Translation (MT) has enabled one to train multilingual Neural MT (NMT) systems that can translate between multiple languages and are also capable of performing zero-shot translation. However, little attention has been paid to leveraging representations learned by a multilingual NMT system to enable zero-shot multilinguality in other NLP tasks. In this paper, we demonstrate a simple framework, a multilingual Encoder-Classifier, for cross-lingual transfer learning by reusing the encoder from a multilingual NMT system and stitching it with a task-specific classifier component. Our proposed model achieves significant improvements in the English setup on three benchmark tasks - Amazon Reviews, SST and SNLI. Further, our system can perform classification in a new language for which no classification data was seen during training, showing that zero-shot classification is possible and remarkably competitive. In order to understand the underlying factors contributing to this finding, we conducted a series of analyses on the effect of the shared vocabulary, the training data type for NMT, classifier complexity, encoder representation power, and model generalization on zero-shot performance. Our results provide strong evidence that the representations learned from multilingual NMT systems are widely applicable across languages and tasks.

##### Abstract (translated by Google)
将大型监督任务中的表示转移到下游任务已经在诸如计算机视觉和自然语言处理（NLP）之类的AI领域中显示出有希望的结果。同时，机器翻译（MT）的最新进展使人们能够训练多语言神经MT（NMT）系统，该系统可以在多种语言之间进行转换，并且还能够执行零镜头转换。然而，很少注意利用多语言NMT系统学习的表示来实现其他NLP任务中的零射击多语言。在本文中，我们通过重用多语言NMT系统中的编码器并将其与特定于任务的分类器组件拼接，演示了一个简单的框架，多语言编码器 - 分类器，用于跨语言传输学习。我们提出的模型在三个基准任务 - 亚马逊评论，SST和SNLI上的英语设置方面取得了重大改进。此外，我们的系统可以在训练期间没有看到分类数据的新语言中进行分类，表明零射击分类是可能的并且具有显着的竞争性。为了理解导致这一发现的潜在因素，我们对共享词汇的影响，NMT的训练数据类型，分类器复杂度，编码器表示能力以及零射击性能的模型推广进行了一系列分析。我们的结果提供了强有力的证据，表明从多语言NMT系统中学到的表示可广泛应用于语言和任务。

##### URL
[http://arxiv.org/abs/1809.04686](http://arxiv.org/abs/1809.04686)

##### PDF
[http://arxiv.org/pdf/1809.04686](http://arxiv.org/pdf/1809.04686)

