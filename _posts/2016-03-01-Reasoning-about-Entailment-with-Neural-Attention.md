---
layout: post
title: "Reasoning about Entailment with Neural Attention"
date: 2016-03-01 10:32:06
categories: arXiv_CL
tags: arXiv_CL Attention Relation
author: Tim Rocktäschel, Edward Grefenstette, Karl Moritz Hermann, Tomáš Kočiský, Phil Blunsom
mathjax: true
---

* content
{:toc}

##### Abstract
While most approaches to automatically recognizing entailment relations have used classifiers employing hand engineered features derived from complex natural language processing pipelines, in practice their performance has been only slightly better than bag-of-word pair classifiers using only lexical similarity. The only attempt so far to build an end-to-end differentiable neural network for entailment failed to outperform such a simple similarity classifier. In this paper, we propose a neural model that reads two sentences to determine entailment using long short-term memory units. We extend this model with a word-by-word neural attention mechanism that encourages reasoning over entailments of pairs of words and phrases. Furthermore, we present a qualitative analysis of attention weights produced by this model, demonstrating such reasoning capabilities. On a large entailment dataset this model outperforms the previous best neural model and a classifier with engineered features by a substantial margin. It is the first generic end-to-end differentiable system that achieves state-of-the-art accuracy on a textual entailment dataset.

##### Abstract (translated by Google)
虽然大多数自动识别蕴含关系的方法使用了从复杂的自然语言处理流水线中获得的使用手工设计特征的分类器，但是实际上它们的性能仅仅比仅使用词汇相似度的词袋对分类器略好。到目前为止，为了构建一个端到端的可区分神经网络而进行的唯一尝试未能超越这样一个简单的相似度分类器。在本文中，我们提出了一个神经模型，它使用长短期记忆单位来读取两个句子来确定蕴涵。我们用逐字的神经注意机制来扩展这个模型，这个机制鼓励推理成对的单词和短语。此外，我们提出了这个模型产生的注意力量的定性分析，展示了这种推理能力。在一个大的蕴含数据集上，这个模型胜过了以前最好的神经模型和一个具有工程特征的分类器。它是第一个通用的端到端微分系统，可以在文本包含数据集上实现最新的准确性。

##### URL
[https://arxiv.org/abs/1509.06664](https://arxiv.org/abs/1509.06664)

##### PDF
[https://arxiv.org/pdf/1509.06664](https://arxiv.org/pdf/1509.06664)

