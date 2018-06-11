---
layout: post
title: "Multilingual Neural Machine Translation with Task-Specific Attention"
date: 2018-06-08 17:18:26
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Graeme Blackwood, Miguel Ballesteros, Todd Ward
mathjax: true
---

* content
{:toc}

##### Abstract
Multilingual machine translation addresses the task of translating between multiple source and target languages. We propose task-specific attention models, a simple but effective technique for improving the quality of sequence-to-sequence neural multilingual translation. Our approach seeks to retain as much of the parameter sharing generalization of NMT models as possible, while still allowing for language-specific specialization of the attention model to a particular language-pair or task. Our experiments on four languages of the Europarl corpus show that using a target-specific model of attention provides consistent gains in translation quality for all possible translation directions, compared to a model in which all parameters are shared. We observe improved translation quality even in the (extreme) low-resource zero-shot translation directions for which the model never saw explicitly paired parallel data.

##### Abstract (translated by Google)
多语言机器翻译解决了在多种源语言和目标语言之间进行翻译的任务。我们提出了特定于任务的注意模型，这是一种简单而有效的技术，用于提高序列到序列神经多语翻译的质量。我们的方法试图尽可能多地保留NMT模型的参数共享泛化，同时仍然允许针对特定语言对或任务的特定语言专用化注意模型。我们对Europarl语料库的四种语言进行的实验表明，与所有参数共享的模型相比，使用特定目标特定模型为所有可能的翻译方向提供了翻译质量的一致增益。即使在模型从未见过明确配对的并行数据的（极端）低资源零点转换方向，我们也观察到翻译质量得到了提高。

##### URL
[http://arxiv.org/abs/1806.03280](http://arxiv.org/abs/1806.03280)

##### PDF
[http://arxiv.org/pdf/1806.03280](http://arxiv.org/pdf/1806.03280)

