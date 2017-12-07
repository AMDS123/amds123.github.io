---
layout: post
title: "Multi-Dialect Speech Recognition With A Single Sequence-To-Sequence Model"
date: 2017-12-05 09:39:18
categories: arXiv_SD
tags: arXiv_SD GAN Speech_Recognition Recognition
author: Bo Li, Tara N. Sainath, Khe Chai Sim, Michiel Bacchiani, Eugene Weinstein, Patrick Nguyen, Zhifeng Chen, Yonghui Wu, Kanishka Rao
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence models provide a simple and elegant solution for building speech recognition systems by folding separate components of a typical system, namely acoustic (AM), pronunciation (PM) and language (LM) models into a single neural network. In this work, we look at one such sequence-to-sequence model, namely listen, attend and spell (LAS), and explore the possibility of training a single model to serve different English dialects, which simplifies the process of training multi-dialect systems without the need for separate AM, PM and LMs for each dialect. We show that simply pooling the data from all dialects into one LAS model falls behind the performance of a model fine-tuned on each dialect. We then look at incorporating dialect-specific information into the model, both by modifying the training targets by inserting the dialect symbol at the end of the original grapheme sequence and also feeding a 1-hot representation of the dialect information into all layers of the model. Experimental results on seven English dialects show that our proposed system is effective in modeling dialect variations within a single LAS model, outperforming a LAS model trained individually on each of the seven dialects by 3.1 ~ 16.5% relative.

##### Abstract (translated by Google)
序列 - 序列模型通过将典型系统（即声学（AM），发音（PM）和语言（LM）模型）的单独组件折叠成单个神经网络来为构建语音识别系统提供简单且优雅的解决方案。在这项工作中，我们看一个序列到序列的模型，即listen，attend和spell（LAS），并探讨训练一个单一模型服务不同英语方言的可能性，这简化了多方言训练的过程系统，而不需要为每种方言单独使用AM，PM和LM。我们表明，简单地将来自所有方言的数据集中到一个LAS模型落后于每个方言的微调模型的性能。然后，我们考虑将特定方言的信息结合到模型中，通过在原始字形序列的末尾插入方言符号来修改训练目标，并且还将方言信息的1热表示馈送到模型的所有层。对7个英语方言的实验结果表明，我们提出的系统在一个单一的LAS模型内对方言变异建模是有效的，相对于7个方言中的每一个方言训练的LAS模型相对于单独训练的相对3.1〜16.5％更为有效。

##### URL
[http://arxiv.org/abs/1712.01541](http://arxiv.org/abs/1712.01541)

##### PDF
[http://arxiv.org/pdf/1712.01541](http://arxiv.org/pdf/1712.01541)

