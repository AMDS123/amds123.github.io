---
layout: post
title: "Multiresolution Recurrent Neural Networks: An Application to Dialogue Response Generation"
date: 2016-06-14 02:01:16
categories: arXiv_CL
tags: arXiv_CL RNN
author: Iulian Vlad Serban, Tim Klinger, Gerald Tesauro, Kartik Talamadupula, Bowen Zhou, Yoshua Bengio, Aaron Courville
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the multiresolution recurrent neural network, which extends the sequence-to-sequence framework to model natural language generation as two parallel discrete stochastic processes: a sequence of high-level coarse tokens, and a sequence of natural language tokens. There are many ways to estimate or learn the high-level coarse tokens, but we argue that a simple extraction procedure is sufficient to capture a wealth of high-level discourse semantics. Such procedure allows training the multiresolution recurrent neural network by maximizing the exact joint log-likelihood over both sequences. In contrast to the standard log- likelihood objective w.r.t. natural language tokens (word perplexity), optimizing the joint log-likelihood biases the model towards modeling high-level abstractions. We apply the proposed model to the task of dialogue response generation in two challenging domains: the Ubuntu technical support domain, and Twitter conversations. On Ubuntu, the model outperforms competing approaches by a substantial margin, achieving state-of-the-art results according to both automatic evaluation metrics and a human evaluation study. On Twitter, the model appears to generate more relevant and on-topic responses according to automatic evaluation metrics. Finally, our experiments demonstrate that the proposed model is more adept at overcoming the sparsity of natural language and is better able to capture long-term structure.

##### Abstract (translated by Google)
我们引入了多分辨率递归神经网络，它扩展了序列到序列框架，将自然语言生成建模为两个并行的离散随机过程：一系列高级粗糙的令牌和一系列自然语言的令牌。有很多方法可以估计或者学习高级粗糙的令牌，但是我们认为一个简单的提取过程足以捕捉到大量的高级语义语义。这样的程序允许通过最大化两个序列上的精确联合对数似然来训练多分辨率递归神经网络。与标准的对数似然目标w.r.t相反自然语言令牌（词困惑），优化联合对数似然使得模型偏向于建模高级抽象。我们将所提议的模型应用于两个具有挑战性的领域中的对话响应生成任务：Ubuntu技术支持域和Twitter对话。在Ubuntu上，该模型的性能优于竞争方法，实现了自动评估指标和人类评估研究的最新成果。在Twitter上，该模型似乎根据自动评估指标生成更多相关和主题回复。最后，我们的实验证明，所提出的模型更善于克服自然语言的稀疏性，更能捕捉到长期的结构。

##### URL
[https://arxiv.org/abs/1606.00776](https://arxiv.org/abs/1606.00776)

##### PDF
[https://arxiv.org/pdf/1606.00776](https://arxiv.org/pdf/1606.00776)

