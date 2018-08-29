---
layout: post
title: "Unsupervised Learning of Syntactic Structure with Invertible Neural Projections"
date: 2018-08-28 04:33:25
categories: arXiv_CL
tags: arXiv_CL Inference
author: Junxian He, Graham Neubig, Taylor Berg-Kirkpatrick
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised learning of syntactic structure is typically performed using generative models with discrete latent variables and multinomial parameters. In most cases, these models have not leveraged continuous word representations. In this work, we propose a novel generative model that jointly learns discrete syntactic structure and continuous word representations in an unsupervised fashion by cascading an invertible neural network with a structured generative prior. We show that the invertibility condition allows for efficient exact inference and marginal likelihood computation in our model so long as the prior is well-behaved. In experiments we instantiate our approach with both Markov and tree-structured priors, evaluating on two tasks: part-of-speech (POS) induction, and unsupervised dependency parsing without gold POS annotation. On the Penn Treebank, our Markov-structured model surpasses state-of-the-art results on POS induction. Similarly, we find that our tree-structured model achieves state-of-the-art performance on unsupervised dependency parsing for the difficult training condition where neither gold POS annotation nor punctuation-based constraints are available.

##### Abstract (translated by Google)
通常使用具有离散潜变量和多项式参数的生成模型来执行语法结构的无监督学习。在大多数情况下，这些模型没有利用连续的单词表示。在这项工作中，我们提出了一种新的生成模型，通过将可逆神经网络与结构化的生成先验级联，以无监督的方式联合学习离散的句法结构和连续的单词表示。我们证明了可逆性条件允许在我们的模型中进行有效的精确推理和边际似然计算，只要先验表现良好。在实验中，我们使用马尔可夫和树结构先验来实例化我们的方法，评估两个任务：词性（POS）感应，以及没有黄金POS注释的无监督依赖性解析。在Penn Treebank，我们的Markov结构模型超越了POS感应的最新结果。类似地，我们发现我们的树形结构模型在无监督的依赖解析中实现了最先进的性能，用于难以训练的条件，其中金POS注释和基于标点符号的约束都不可用。

##### URL
[http://arxiv.org/abs/1808.09111](http://arxiv.org/abs/1808.09111)

##### PDF
[http://arxiv.org/pdf/1808.09111](http://arxiv.org/pdf/1808.09111)

