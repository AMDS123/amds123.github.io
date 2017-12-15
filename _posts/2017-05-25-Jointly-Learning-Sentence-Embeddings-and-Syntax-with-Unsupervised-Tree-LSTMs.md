---
layout: post
title: "Jointly Learning Sentence Embeddings and Syntax with Unsupervised Tree-LSTMs"
date: 2017-05-25 14:09:48
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Gradient_Descent
author: Jean Maillard, Stephen Clark, Dani Yogatama
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a neural network that represents sentences by composing their words according to induced binary parse trees. We use Tree-LSTM as our composition function, applied along a tree structure found by a fully differentiable natural language chart parser. Our model simultaneously optimises both the composition function and the parser, thus eliminating the need for externally-provided parse trees which are normally required for Tree-LSTM. It can therefore be seen as a tree-based RNN that is unsupervised with respect to the parse trees. As it is fully differentiable, our model is easily trained with an off-the-shelf gradient descent method and backpropagation. We demonstrate that it achieves better performance compared to various supervised Tree-LSTM architectures on a textual entailment task and a reverse dictionary task.

##### Abstract (translated by Google)
我们引入了一个神经网络，通过根据诱导的二进制解析树来组合他们的词来表示句子。我们使用Tree-LSTM作为我们的组合函数，沿着由完全可区分的自然语言图表分析器找到的树结构进行应用。我们的模型同时优化了组合函数和解析器，从而消除了对Tree-LSTM通常需要的外部提供的解析树的需求。因此可以看作是基于树的RNN，其对于分析树是无监督的。由于它是完全可微的，我们的模型很容易用现成的梯度下降法和反向传播训练。我们证明，与各种受监督的Tree-LSTM体系结构相比，它在文本包含任务和反向字典任务上实现了更好的性能。

##### URL
[https://arxiv.org/abs/1705.09189](https://arxiv.org/abs/1705.09189)

##### PDF
[https://arxiv.org/pdf/1705.09189](https://arxiv.org/pdf/1705.09189)

