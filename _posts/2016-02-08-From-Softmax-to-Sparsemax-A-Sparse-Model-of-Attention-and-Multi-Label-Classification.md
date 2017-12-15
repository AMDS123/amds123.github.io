---
layout: post
title: "From Softmax to Sparsemax: A Sparse Model of Attention and Multi-Label Classification"
date: 2016-02-08 09:41:36
categories: arXiv_SD
tags: arXiv_SD Sparse Attention Inference Classification
author: André F. T. Martins, Ramón Fernandez Astudillo
mathjax: true
---

* content
{:toc}

##### Abstract
We propose sparsemax, a new activation function similar to the traditional softmax, but able to output sparse probabilities. After deriving its properties, we show how its Jacobian can be efficiently computed, enabling its use in a network trained with backpropagation. Then, we propose a new smooth and convex loss function which is the sparsemax analogue of the logistic loss. We reveal an unexpected connection between this new loss and the Huber classification loss. We obtain promising empirical results in multi-label classification problems and in attention-based neural networks for natural language inference. For the latter, we achieve a similar performance as the traditional softmax, but with a selective, more compact, attention focus.

##### Abstract (translated by Google)
我们提出了一个新的激活函数sparsemax，类似于传统的softmax，但能够输出稀疏概率。在得到它的属性之后，我们展示了它的雅可比矩阵如何被有效地计算，使得它能够在反向传播训练的网络中使用。然后，我们提出一个新的光滑凸损失函数，它是逻辑损失的稀疏最大模拟。我们发现这个新的损失和Huber分类损失之间的意外联系。我们在多标签分类问题和基于注意力的自然语言推理的神经网络中获得了有前景的实证结果。对于后者，我们达到了与传统softmax类似的性能，但是具有选择性，更紧凑的关注焦点。

##### URL
[https://arxiv.org/abs/1602.02068](https://arxiv.org/abs/1602.02068)

##### PDF
[https://arxiv.org/pdf/1602.02068](https://arxiv.org/pdf/1602.02068)

