---
layout: post
title: "Attention Is All You Need"
date: 2017-12-06 03:30:32
categories: arXiv_CL
tags: arXiv_CL CNN
author: Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, Illia Polosukhin
mathjax: true
---

* content
{:toc}

##### Abstract
The dominant sequence transduction models are based on complex recurrent or convolutional neural networks in an encoder-decoder configuration. The best performing models also connect the encoder and decoder through an attention mechanism. We propose a new simple network architecture, the Transformer, based solely on attention mechanisms, dispensing with recurrence and convolutions entirely. Experiments on two machine translation tasks show these models to be superior in quality while being more parallelizable and requiring significantly less time to train. Our model achieves 28.4 BLEU on the WMT 2014 English-to-German translation task, improving over the existing best results, including ensembles by over 2 BLEU. On the WMT 2014 English-to-French translation task, our model establishes a new single-model state-of-the-art BLEU score of 41.8 after training for 3.5 days on eight GPUs, a small fraction of the training costs of the best models from the literature. We show that the Transformer generalizes well to other tasks by applying it successfully to English constituency parsing both with large and limited training data.

##### Abstract (translated by Google)
主导序列转导模型基于编码器 - 解码器配置中的复杂递归或卷积神经网络。性能最好的型号还通过关注机制连接编码器和解码器。我们提出了一个新的简单的网络架构，Transformer，完全基于注意机制，完全避免了循环和卷积。对两个机器翻译任务的实验表明，这些模型在质量上是优越的，同时更可并行化，并且需要大量的时间来训练。我们的模型在WMT 2014英语至德语翻译任务上达到了28.4 BLEU，改进了现有的最佳结果，其中包括超过2 BLEU的合奏。在WMT 2014英文到法文的翻译任务中，我们的模型在8个GPU上训练了3.5天之后，建立了新的单模式最先进BLEU成绩为41.8，这是培训成本的一小部分来自文学的模型。我们表明，变压器一般适用于其他任务成功地应用于英语选区解析大量和有限的训练数据。

##### URL
[http://arxiv.org/abs/1706.03762](http://arxiv.org/abs/1706.03762)

##### PDF
[http://arxiv.org/pdf/1706.03762](http://arxiv.org/pdf/1706.03762)

