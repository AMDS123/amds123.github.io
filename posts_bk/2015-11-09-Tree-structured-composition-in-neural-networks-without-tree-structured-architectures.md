---
layout: post
title: "Tree-structured composition in neural networks without tree-structured architectures"
date: 2015-11-09 19:45:09
categories: arXiv_CL
tags: arXiv_CL RNN
author: Samuel R. Bowman, Christopher D. Manning, Christopher Potts
mathjax: true
---

* content
{:toc}

##### Abstract
Tree-structured neural networks encode a particular tree geometry for a sentence in the network design. However, these models have at best only slightly outperformed simpler sequence-based models. We hypothesize that neural sequence models like LSTMs are in fact able to discover and implicitly use recursive compositional structure, at least for tasks with clear cues to that structure in the data. We demonstrate this possibility using an artificial data task for which recursive compositional structure is crucial, and find an LSTM-based sequence model can indeed learn to exploit the underlying tree structure. However, its performance consistently lags behind that of tree models, even on large training sets, suggesting that tree-structured models are more effective at exploiting recursive structure.

##### Abstract (translated by Google)
树形结构的神经网络为网络设计中的句子编码特定的树形几何。然而，这些模型最好只略胜过简单的基于序列的模型。我们假设像LSTM这样的神经序列模型实际上能够发现和隐含地使用递归组合结构，至少对于在数据中具有明确提示的任务。我们使用一个人工数据任务证明了这种可能性，对于这种任务，递归组合结构是至关重要的，并且发现基于LSTM的序列模型确实可以学习利用底层树结构。然而，即使是在大型的训练集上，它的性能仍然落后于树模型，这表明树型结构模型在利用递归结构方面更为有效。

##### URL
[https://arxiv.org/abs/1506.04834](https://arxiv.org/abs/1506.04834)

##### PDF
[https://arxiv.org/pdf/1506.04834](https://arxiv.org/pdf/1506.04834)

