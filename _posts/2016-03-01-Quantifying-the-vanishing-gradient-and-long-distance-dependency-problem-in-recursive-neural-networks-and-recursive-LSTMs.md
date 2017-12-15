---
layout: post
title: "Quantifying the vanishing gradient and long distance dependency problem in recursive neural networks and recursive LSTMs"
date: 2016-03-01 19:45:25
categories: arXiv_SD
tags: arXiv_SD Sentiment Embedding RNN Memory_Networks
author: Phong Le, Willem Zuidema
mathjax: true
---

* content
{:toc}

##### Abstract
Recursive neural networks (RNN) and their recently proposed extension recursive long short term memory networks (RLSTM) are models that compute representations for sentences, by recursively combining word embeddings according to an externally provided parse tree. Both models thus, unlike recurrent networks, explicitly make use of the hierarchical structure of a sentence. In this paper, we demonstrate that RNNs nevertheless suffer from the vanishing gradient and long distance dependency problem, and that RLSTMs greatly improve over RNN's on these problems. We present an artificial learning task that allows us to quantify the severity of these problems for both models. We further show that a ratio of gradients (at the root node and a focal leaf node) is highly indicative of the success of backpropagation at optimizing the relevant weights low in the tree. This paper thus provides an explanation for existing, superior results of RLSTMs on tasks such as sentiment analysis, and suggests that the benefits of including hierarchical structure and of including LSTM-style gating are complementary.

##### Abstract (translated by Google)
递归神经网络（RNN）及其最近提出的扩展递归长期记忆网络（RLSTM）是通过根据外部提供的分析树递归地组合词嵌入来计算句子表示的模型。因此，与经常性网络不同，这两种模式都明确地利用句子的层次结构。在本文中，我们证明RNNs仍然受到消失梯度和长距离依赖问题的困扰，并且RLSTM在这些问题上大大改善了RNN。我们提出一个人工学习任务，使我们能够量化这两个模型的这些问题的严重性。我们进一步表明，梯度（在根节点和焦点叶节点）的比率高度表明反向传播的成功，以优化树中低的相关权重。因此，本文提供了对RLSTM在情感分析等任务上的现有优秀结果的解释，并且表明包括等级结构和包括LSTM式门控的好处是相辅相成的。

##### URL
[https://arxiv.org/abs/1603.00423](https://arxiv.org/abs/1603.00423)

##### PDF
[https://arxiv.org/pdf/1603.00423](https://arxiv.org/pdf/1603.00423)

