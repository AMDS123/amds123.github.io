---
layout: post
title: "Generating Sentences from a Continuous Space"
date: 2016-05-12 20:51:23
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Samuel R. Bowman, Luke Vilnis, Oriol Vinyals, Andrew M. Dai, Rafal Jozefowicz, Samy Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
The standard recurrent neural network language model (RNNLM) generates sentences one word at a time and does not work from an explicit global sentence representation. In this work, we introduce and study an RNN-based variational autoencoder generative model that incorporates distributed latent representations of entire sentences. This factorization allows it to explicitly model holistic properties of sentences such as style, topic, and high-level syntactic features. Samples from the prior over these sentence representations remarkably produce diverse and well-formed sentences through simple deterministic decoding. By examining paths through this latent space, we are able to generate coherent novel sentences that interpolate between known sentences. We present techniques for solving the difficult learning problem presented by this model, demonstrate its effectiveness in imputing missing words, explore many interesting properties of the model's latent sentence space, and present negative results on the use of the model in language modeling.

##### Abstract (translated by Google)
标准递归神经网络语言模型（RNNLM）一次生成一个单词，并且不能从明确的全局句子表示中起作用。在这项工作中，我们介绍和研究了一个基于RNN的变分自动编码器生成模型，其中包含整个句子的分布式潜在表示。这种因式分解使得它可以明确地建模诸如风格，主题和高级语法特征等句子的整体属性。通过简单的确定性解码，来自先前的这些句子表示的样本显着地产生了多样的，格式良好的句子。通过检查通过这个潜在的空间的路径，我们能够产生内插在已知句子之间的连贯的新的句子。我们提出了解决这个模型提出的困难的学习问题的技巧，证明了它在填补缺失的单词方面的有效性，探索了模型潜在句子空间的许多有趣的性质，并且在模型在语言建模中的使用上呈现出负面的结果。

##### URL
[https://arxiv.org/abs/1511.06349](https://arxiv.org/abs/1511.06349)

##### PDF
[https://arxiv.org/pdf/1511.06349](https://arxiv.org/pdf/1511.06349)

