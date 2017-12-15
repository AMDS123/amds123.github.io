---
layout: post
title: "Sequence Level Training with Recurrent Neural Networks"
date: 2016-05-06 21:18:46
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Marc'Aurelio Ranzato, Sumit Chopra, Michael Auli, Wojciech Zaremba
mathjax: true
---

* content
{:toc}

##### Abstract
Many natural language processing applications use language models to generate text. These models are typically trained to predict the next word in a sequence, given the previous words and some context such as an image. However, at test time the model is expected to generate the entire sequence from scratch. This discrepancy makes generation brittle, as errors may accumulate along the way. We address this issue by proposing a novel sequence level training algorithm that directly optimizes the metric used at test time, such as BLEU or ROUGE. On three different tasks, our approach outperforms several strong baselines for greedy generation. The method is also competitive when these baselines employ beam search, while being several times faster.

##### Abstract (translated by Google)
许多自然语言处理应用程序使用语言模型来生成文本。这些模型通常被训练用于预测序列中的下一个单词，给出前面的单词和诸如图像之类的上下文。但是，在测试时间，模型预计会从头开始生成整个序列。这种差异使得世代变得脆弱，因为错误可能会一路积累。我们通过提出一种新的序列级训练算法来解决这个问题，该算法直接优化了测试时使用的度量，例如BLEU或ROUGE。在三个不同的任务中，我们的方法胜过了几个强大的贪婪生成基线。当这些基线使用波束搜索时，该方法也是有竞争力的，同时要快几倍。

##### URL
[https://arxiv.org/abs/1511.06732](https://arxiv.org/abs/1511.06732)

##### PDF
[https://arxiv.org/pdf/1511.06732](https://arxiv.org/pdf/1511.06732)

