---
layout: post
title: "Learning to update Auto-associative Memory in Recurrent Neural Networks for Improving Sequence Memorization"
date: 2017-10-03 14:31:03
categories: arXiv_CV
tags: arXiv_CV Attention Represenation_Learning RNN
author: Wei Zhang, Bowen Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to remember long sequences remains a challenging task for recurrent neural networks. Register memory and attention mechanisms were both proposed to resolve the issue with either high computational cost to retain memory differentiability, or by discounting the RNN representation learning towards encoding shorter local contexts than encouraging long sequence encoding. Associative memory, which studies the compression of multiple patterns in a fixed size memory, were rarely considered in recent years. Although some recent work tries to introduce associative memory in RNN and mimic the energy decay process in Hopfield nets, it inherits the shortcoming of rule-based memory updates, and the memory capacity is limited. This paper proposes a method to learn the memory update rule jointly with task objective to improve memory capacity for remembering long sequences. Also, we propose an architecture that uses multiple such associative memory for more complex input encoding. We observed some interesting facts when compared to other RNN architectures on some well-studied sequence learning tasks.

##### Abstract (translated by Google)
学习记忆长序列对于递归神经网络来说仍然是具有挑战性的任务。注册记忆和注意机制都是为了解决这个问题，或者是为了保留存储器的可分辨性，或者通过折扣RNN表示学习来编码更短的本地上下文，而不是鼓励长序列编码来解决这个问题。联想记忆，研究在一个固定大小的记忆多个模式的压缩，近年来很少考虑。尽管最近的一些工作试图在RNN中引入联想记忆，并模拟Hopfield网络中的能量衰减过程，但它仍然存在着基于规则的内存更新的缺点，而且内存容量有限。为了提高记忆长序列的记忆容量，本文提出了一种学习记忆更新规则的方法。此外，我们提出了一个架构，使用多个这样的联想记忆更复杂的输入编码。与其他RNN架构相比，我们观察到一些有趣的事实，关于一些经过充分研究的序列学习任务。

##### URL
[https://arxiv.org/abs/1709.06493](https://arxiv.org/abs/1709.06493)

##### PDF
[https://arxiv.org/pdf/1709.06493](https://arxiv.org/pdf/1709.06493)

