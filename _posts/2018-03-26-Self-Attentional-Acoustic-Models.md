---
layout: post
title: "Self-Attentional Acoustic Models"
date: 2018-03-26 11:36:36
categories: arXiv_CL
tags: arXiv_CL Attention RNN
author: Matthias Sperber, Jan Niehues, Graham Neubig, Sebastian Stüker, Alex Waibel
mathjax: true
---

* content
{:toc}

##### Abstract
Self-attention is a method of encoding sequences of vectors by relating these vectors to each-other based on pairwise similarities. These models have recently shown promising results for modeling discrete sequences, but they are non-trivial to apply to acoustic modeling due to computational and modeling issues. In this paper, we apply self-attention to acoustic modeling, proposing several improvements to mitigate these issues: First, self-attention memory grows quadratically in the sequence length, which we address through a downsampling technique. Second, we find that previous approaches to incorporate position information into the model are unsuitable and explore other representations and hybrid models to this end. Third, to stress the importance of local context in the acoustic signal, we propose a Gaussian biasing approach that allows explicit control over the context range. Experiments find that our model approaches a strong baseline based on LSTMs with network-in-network connections while being much faster to compute. Besides speed, we find that interpretability is a strength of self-attentional acoustic models, and demonstrate that self-attention heads learn a linguistically plausible division of labor.

##### Abstract (translated by Google)
自我关注是一种通过基于成对相似性将这些向量彼此相关来编码向量序列的方法。这些模型最近显示了对离散序列进行建模的有希望的结果，但由于计算和建模问题，这些模型不适用于声学建模。在本文中，我们将自我注意力应用于声学建模，提出了若干改进以缓解这些问题：首先，自我注意记忆在序列长度中以二次方增长，我们通过下采样技术解决。其次，我们发现以前将位置信息并入模型的方法是不合适的，为此探索其他表示和混合模型。第三，为了强调声信号中本地环境的重要性，我们提出了一种高斯偏置方法，允许对上下文范围进行显式控制。实验发现，我们的模型基于带网络连接的LSTM而接近强大的基线，同时计算速度更快。除了速度之外，我们发现可解释性是自我注意声学模型的强项，并且表明自我关注头正在学习语言上合理的分工。

##### URL
[https://arxiv.org/abs/1803.09519](https://arxiv.org/abs/1803.09519)

##### PDF
[https://arxiv.org/pdf/1803.09519](https://arxiv.org/pdf/1803.09519)

