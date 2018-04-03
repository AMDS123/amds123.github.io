---
layout: post
title: "A Novel Learnable Dictionary Encoding Layer for End-to-End Language Identification"
date: 2018-04-02 03:31:01
categories: arXiv_SD
tags: arXiv_SD
author: Weicheng Cai, Zexin Cai, Xiang Zhang, Xiaoqi Wang, Ming Li
mathjax: true
---

* content
{:toc}

##### Abstract
A novel learnable dictionary encoding layer is proposed in this paper for end-to-end language identification. It is inline with the conventional GMM i-vector approach both theoretically and practically. We imitate the mechanism of traditional GMM training and Supervector encoding procedure on the top of CNN. The proposed layer can accumulate high-order statistics from variable-length input sequence and generate an utterance level fixed-dimensional vector representation. Unlike the conventional methods, our new approach provides an end-to-end learning framework, where the inherent dictionary are learned directly from the loss function. The dictionaries and the encoding representation for the classifier are learned jointly. The representation is orderless and therefore appropriate for language identification. We conducted a preliminary experiment on NIST LRE07 closed-set task, and the results reveal that our proposed dictionary encoding layer achieves significant error reduction comparing with the simple average pooling.

##### Abstract (translated by Google)
本文提出了一种新颖的可学习字典编码层，用于端到端的语言识别。它与传统的GMM i-vector方法在理论和实践上都是一致的。我们模仿传统的GMM训练和Supervector编码程序的机制在CNN的顶端。所提出的层可以从可变长度输入序列中累积高阶统计量并产生话语水平的固定维向量表示。与传统方法不同，我们的新方法提供了一个端到端的学习框架，其中固有字典直接从损失函数中学习。词典和分类器的编码表示是共同学习的。该表示是无序的，因此适用于语言识别。我们对NIST LRE07封闭任务进行了初步实验，结果表明我们提出的字典编码层与简单平均池相比显着减少了错误。

##### URL
[http://arxiv.org/abs/1804.00385](http://arxiv.org/abs/1804.00385)

##### PDF
[http://arxiv.org/pdf/1804.00385](http://arxiv.org/pdf/1804.00385)

