---
layout: post
title: "Universal Transformers"
date: 2018-07-10 18:39:15
categories: arXiv_CL
tags: arXiv_CL Attention RNN Language_Model
author: Mostafa Dehghani, Stephan Gouws, Oriol Vinyals, Jakob Uszkoreit, &#x141;ukasz Kaiser
mathjax: true
---

* content
{:toc}

##### Abstract
Self-attentive feed-forward sequence models have been shown to achieve impressive results on sequence modeling tasks, thereby presenting a compelling alternative to recurrent neural networks (RNNs) which has remained the de-facto standard architecture for many sequence modeling problems to date. Despite these successes, however, feed-forward sequence models like the Transformer fail to generalize in many tasks that recurrent models handle with ease (e.g. copying when the string lengths exceed those observed at training time). Moreover, and in contrast to RNNs, the Transformer model is not computationally universal, limiting its theoretical expressivity. In this paper we propose the Universal Transformer which addresses these practical and theoretical shortcomings and we show that it leads to improved performance on several tasks. Instead of recurring over the individual symbols of sequences like RNNs, the Universal Transformer repeatedly revises its representations of all symbols in the sequence with each recurrent step. In order to combine information from different parts of a sequence, it employs a self-attention mechanism in every recurrent step. Assuming sufficient memory, its recurrence makes the Universal Transformer computationally universal. We further employ an adaptive computation time (ACT) mechanism to allow the model to dynamically adjust the number of times the representation of each position in a sequence is revised. Beyond saving computation, we show that ACT can improve the accuracy of the model. Our experiments show that on various algorithmic tasks and a diverse set of large-scale language understanding tasks the Universal Transformer generalizes significantly better and outperforms both a vanilla Transformer and an LSTM in machine translation, and achieves a new state of the art on the bAbI linguistic reasoning task and the challenging LAMBADA language modeling task.

##### Abstract (translated by Google)
自我注意的前馈序列模型已经显示出在序列建模任务上取得了令人印象深刻的结果，从而为递归神经网络（RNN）提供了一个引人注目的替代方案，这仍然是迄今为止许多序列建模问题的事实上的标准体系结构。然而，尽管取得了这些成功，但像Transformer这样的前馈序列模型却无法在复发模型轻松处理的许多任务中进行概括（例如，当弦长超过训练时观察到的那些时复制）。此外，与RNN相比，变压器模型在计算上并不普及，限制了其理论表现力。在本文中，我们提出了通用变压器，它解决了这些实际和理论上的缺点，并且我们证明它可以改善几项任务的性能。通用变换器不是对像RNN这样的序列的各个符号重复出现，而是通过每个循环步骤反复修改其对序列中所有符号的表示。为了组合来自序列的不同部分的信息，它在每个循环步骤中采用自我关注机制。假设有足够的内存，它的重复使得Universal Transformer在计算上具有通用性。我们进一步采用自适应计算时间（ACT）机制，以允许模型动态调整序列中每个位置的表示被修改的次数。除了节省计算，我们还表明ACT可以提高模型的准确性。我们的实验表明，在各种算法任务和各种大规模语言理解任务中，Universal Transformer可以更好地推广并在机器翻译中优于香草变换器和LSTM，并在bAbI语言上实现了最新的技术水平。推理任务和具有挑战性的LAMBADA语言建模任务。

##### URL
[http://arxiv.org/abs/1807.03819](http://arxiv.org/abs/1807.03819)

##### PDF
[http://arxiv.org/pdf/1807.03819](http://arxiv.org/pdf/1807.03819)

