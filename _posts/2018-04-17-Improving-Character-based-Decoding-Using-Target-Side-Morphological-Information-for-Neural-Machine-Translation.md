---
layout: post
title: "Improving Character-based Decoding Using Target-Side Morphological Information for Neural Machine Translation"
date: 2018-04-17 23:54:26
categories: arXiv_CL
tags: arXiv_CL NMT Prediction
author: Peyman Passban, Qun Liu, Andy Way
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, neural machine translation (NMT) has emerged as a powerful alternative to conventional statistical approaches. However, its performance drops considerably in the presence of morphologically rich languages (MRLs). Neural engines usually fail to tackle the large vocabulary and high out-of-vocabulary (OOV) word rate of MRLs. Therefore, it is not suitable to exploit existing word-based models to translate this set of languages. In this paper, we propose an extension to the state-of-the-art model of Chung et al. (2016), which works at the character level and boosts the decoder with target-side morphological information. In our architecture, an additional morphology table is plugged into the model. Each time the decoder samples from a target vocabulary, the table sends auxiliary signals from the most relevant affixes in order to enrich the decoder's current state and constrain it to provide better predictions. We evaluated our model to translate English into German, Russian, and Turkish as three MRLs and observed significant improvements.

##### Abstract (translated by Google)
最近，神经机器翻译（NMT）已经成为常规统计方法的有力替代品。然而，在形态丰富的语言（MRLs）的存在下，其性能显着下降。神经引擎通常无法解决大量的词汇量和高的词汇量（OOV）MRL字率。因此，利用现有的基于词的模型来翻译这组语言是不合适的。在本文中，我们提出了对Chung等人的最先进模型的扩展。 （2016），它在字符级别工作，并用目标端形态信息来提升解码器。在我们的体系结构中，附加的形态表被插入到模型中。每次解码器从目标词汇中抽样时，该表格会发送来自最相关词缀的辅助信号，以丰富解码器的当前状态并对其进行约束以提供更好的预测。我们评估了我们的模型，将英语翻译成德语，俄语和土耳其语三种MRL，并观察到显着的改进。

##### URL
[https://arxiv.org/abs/1804.06506](https://arxiv.org/abs/1804.06506)

##### PDF
[https://arxiv.org/pdf/1804.06506](https://arxiv.org/pdf/1804.06506)

