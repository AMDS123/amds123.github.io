---
layout: post
title: "SparseMAP: Differentiable Sparse Structured Inference"
date: 2018-02-12 18:07:34
categories: arXiv_CL
tags: arXiv_CL Sparse Inference Prediction
author: Vlad Niculae, Andr&#xe9; F. T. Martins, Mathieu Blondel, Claire Cardie
mathjax: true
---

* content
{:toc}

##### Abstract
Structured prediction requires searching over a combinatorial number of structures. To tackle it, we introduce SparseMAP, a new method for sparse structured inference, together with corresponding loss functions. SparseMAP inference is able to automatically select only a few global structures: it is situated between MAP inference, which picks a single structure, and marginal inference, which assigns probability mass to all structures, including implausible ones. Importantly, SparseMAP can be computed using only calls to a MAP oracle, hence it is applicable even to problems where marginal inference is intractable, such as linear assignment. Moreover, thanks to the solution sparsity, gradient backpropagation is efficient regardless of the structure. SparseMAP thus enables us to augment deep neural networks with generic and sparse structured hidden layers. Experiments in dependency parsing and natural language inference reveal competitive accuracy, improved interpretability, and the ability to capture natural language ambiguities, which is attractive for pipeline systems.

##### Abstract (translated by Google)
结构化预测需要通过组合数量的结构进行搜索。为了解决这个问题，我们引入了稀疏结构推理的新方法SparseMAP以及相应的损失函数。 SparseMAP推理能够仅自动选择一些全局结构：它位于MAP推理（它选择单一结构）和边缘推理之间，它为所有结构（包括不合理的结构）分配概率质量。重要的是，SparseMAP可以仅使用对MAP预言器的调用来计算，因此它甚至适用于边缘推断是棘手的问题，例如线性分配。而且，由于解决方案的稀疏性，不管结构如何，梯度反向传播都是高效的。 SparseMAP因此使我们能够用通用和稀疏结构隐藏层来增强深层神经网络。依赖分析和自然语言推理的实验揭示了竞争的准确性，提高的可解释性，以及捕捉自然语言歧义的能力，这对管道系统很有吸引力。

##### URL
[http://arxiv.org/abs/1802.04223](http://arxiv.org/abs/1802.04223)

##### PDF
[http://arxiv.org/pdf/1802.04223](http://arxiv.org/pdf/1802.04223)

