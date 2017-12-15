---
layout: post
title: "Neural Machine Translation via Binary Code Prediction"
date: 2017-04-23 12:38:13
categories: arXiv_CL
tags: arXiv_CL Prediction
author: Yusuke Oda, Philip Arthur, Graham Neubig, Koichiro Yoshino, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new method for calculating the output layer in neural machine translation systems. The method is based on predicting a binary code for each word and can reduce computation time/memory requirements of the output layer to be logarithmic in vocabulary size in the best case. In addition, we also introduce two advanced approaches to improve the robustness of the proposed model: using error-correcting codes and combining softmax and binary codes. Experiments on two English-Japanese bidirectional translation tasks show proposed models achieve BLEU scores that approach the softmax, while reducing memory usage to the order of less than 1/10 and improving decoding speed on CPUs by x5 to x10.

##### Abstract (translated by Google)
在本文中，我们提出了一种计算神经机器翻译系统输出层的新方法。该方法基于预测每个单词的二进制代码，并且可以在最佳情况下将输出层的计算时间/存储器需求减少为对数的词汇大小。此外，我们还介绍了两种先进的方法来提高模型的鲁棒性：使用纠错码，并结合softmax和二进制码。在两个英日双向翻译任务上的实验表明，所提出的模型实现了接近softmax的BLEU分数，同时将存储器使用降低到小于1/10的数量级，并且将CPU上的解码速度提高了x5到x10。

##### URL
[https://arxiv.org/abs/1704.06918](https://arxiv.org/abs/1704.06918)

##### PDF
[https://arxiv.org/pdf/1704.06918](https://arxiv.org/pdf/1704.06918)

