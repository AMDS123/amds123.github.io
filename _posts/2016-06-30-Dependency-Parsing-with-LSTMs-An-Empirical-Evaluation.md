---
layout: post
title: "Dependency Parsing with LSTMs: An Empirical Evaluation"
date: 2016-06-30 04:23:07
categories: arXiv_CL
tags: arXiv_CL Embedding RNN
author: Adhiguna Kuncoro, Yuichiro Sawai, Kevin Duh, Yuji Matsumoto
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a transition-based dependency parser using Recurrent Neural Networks with Long Short-Term Memory (LSTM) units. This extends the feedforward neural network parser of Chen and Manning (2014) and enables modelling of entire sequences of shift/reduce transition decisions. On the Google Web Treebank, our LSTM parser is competitive with the best feedforward parser on overall accuracy and notably achieves more than 3% improvement for long-range dependencies, which has proved difficult for previous transition-based parsers due to error propagation and limited context information. Our findings additionally suggest that dropout regularisation on the embedding layer is crucial to improve the LSTM's generalisation.

##### Abstract (translated by Google)
我们提出了一种基于转换的依赖分析器，它使用带有长期短期记忆（LSTM）单元的递归神经网络。这扩展了Chen和Manning（2014）的前馈神经网络分析器，并能够对整个移位/缩减转换决策序列进行建模。在Google Web Treebank中，我们的LSTM解析器在总体准确性方面与最好的前馈解析器相比具有竞争性，并且显着地实现了远程依赖性的3％以上的改进，这对于之前的基于转换的解析器由于错误传播和有限的上下文信息。我们的研究结果还表明，嵌入层上的辍学正则化对于改善LSTM的泛化至关重要。

##### URL
[https://arxiv.org/abs/1604.06529](https://arxiv.org/abs/1604.06529)

##### PDF
[https://arxiv.org/pdf/1604.06529](https://arxiv.org/pdf/1604.06529)

