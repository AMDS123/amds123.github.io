---
layout: post
title: "Scaling Memory-Augmented Neural Networks with Sparse Reads and Writes"
date: 2016-10-27 22:38:05
categories: arXiv_CV
tags: arXiv_CV Sparse Language_Model Recognition
author: Jack W Rae, Jonathan J Hunt, Tim Harley, Ivo Danihelka, Andrew Senior, Greg Wayne, Alex Graves, Timothy P Lillicrap
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks augmented with external memory have the ability to learn algorithmic solutions to complex tasks. These models appear promising for applications such as language modeling and machine translation. However, they scale poorly in both space and time as the amount of memory grows --- limiting their applicability to real-world domains. Here, we present an end-to-end differentiable memory access scheme, which we call Sparse Access Memory (SAM), that retains the representational power of the original approaches whilst training efficiently with very large memories. We show that SAM achieves asymptotic lower bounds in space and time complexity, and find that an implementation runs $1,\!000\times$ faster and with $3,\!000\times$ less physical memory than non-sparse models. SAM learns with comparable data efficiency to existing models on a range of synthetic tasks and one-shot Omniglot character recognition, and can scale to tasks requiring $100,\!000$s of time steps and memories. As well, we show how our approach can be adapted for models that maintain temporal associations between memories, as with the recently introduced Differentiable Neural Computer.

##### Abstract (translated by Google)
借助外部存储器增强的神经网络能够学习复杂任务的算法解决方案。这些模型似乎对诸如语言建模和机器翻译等应用程序很有前途。然而，随着内存数量的增长，它们在时间和空间上的规模都很小，这限制了它们在现实世界中的适用性。在这里，我们提出了一个端到端的可微内存访问方案，我们称之为稀疏访问内存（SAM），它保留了原始方法的代表性，同时用非常大的内存进行有效的训练。我们证明SAM在空间和时间复杂度方面达到了渐近下界，并且发现一个实现比非稀疏模型运行速度更快，速度更快，速度更快，而且物理内存减少了3倍。 SAM在一系列合成任务和一次性Omniglot字符识别上学习了与现有模型相当的数据效率，并且可以扩展到需要100美元，1000美元时间步长和记忆的任务。同样，我们展示了如何将我们的方法适用于维持记忆之间时间关联的模型，就像最近推出的可微分神经计算机一样。

##### URL
[https://arxiv.org/abs/1610.09027](https://arxiv.org/abs/1610.09027)

##### PDF
[https://arxiv.org/pdf/1610.09027](https://arxiv.org/pdf/1610.09027)

