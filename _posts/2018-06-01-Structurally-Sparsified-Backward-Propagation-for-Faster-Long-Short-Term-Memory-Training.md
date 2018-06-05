---
layout: post
title: "Structurally Sparsified Backward Propagation for Faster Long Short-Term Memory Training"
date: 2018-06-01 19:08:30
categories: arXiv_CL
tags: arXiv_CL Sparse Optimization RNN
author: Maohua Zhu, Jason Clemons, Jeff Pool, Minsoo Rhu, Stephen W. Keckler, Yuan Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Exploiting sparsity enables hardware systems to run neural networks faster and more energy-efficiently. However, most prior sparsity-centric optimization techniques only accelerate the forward pass of neural networks and usually require an even longer training process with iterative pruning and retraining. We observe that artificially inducing sparsity in the gradients of the gates in an LSTM cell has little impact on the training quality. Further, we can enforce structured sparsity in the gate gradients to make the LSTM backward pass up to 45% faster than the state-of-the-art dense approach and 168% faster than the state-of-the-art sparsifying method on modern GPUs. Though the structured sparsifying method can impact the accuracy of a model, this performance gap can be eliminated by mixing our sparse training method and the standard dense training method. Experimental results show that the mixed method can achieve comparable results in a shorter time span than using purely dense training.

##### Abstract (translated by Google)
利用稀疏性，硬件系统可以更快，更节能地运行神经网络。然而，大多数先前的以稀疏为中心的优化技术只能加速神经网络的正向传递，并且通常需要更长的训练过程以及迭代修剪和再训练。我们观察到人为地诱导LSTM细胞门中梯度的稀疏对训练质量影响不大。此外，我们可以在门梯度中实施结构化稀疏性，以使LSTM向后传递比现有技术密集方法快45％，比现代先进稀疏方法快168％图形处理器。尽管结构化稀疏化方法可以影响模型的准确性，但通过混合我们的稀疏训练方法和标准密集训练方法，可以消除这种性能差距。实验结果表明，该混合方法可以在较短的时间范围内实现可比较的结果，而非纯密集训练。

##### URL
[http://arxiv.org/abs/1806.00512](http://arxiv.org/abs/1806.00512)

##### PDF
[http://arxiv.org/pdf/1806.00512](http://arxiv.org/pdf/1806.00512)

