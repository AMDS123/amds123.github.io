---
layout: post
title: "Hierarchical Question Answering for Long Documents"
date: 2017-02-08 07:42:34
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning RNN
author: Eunsol Choi, Daniel Hewlett, Alexandre Lacoste, Illia Polosukhin, Jakob Uszkoreit, Jonathan Berant
mathjax: true
---

* content
{:toc}

##### Abstract
We present a framework for question answering that can efficiently scale to longer documents while maintaining or even improving performance of state-of-the-art models. While most successful approaches for reading comprehension rely on recurrent neural networks (RNNs), running them over long documents is prohibitively slow because it is difficult to parallelize over sequences. Inspired by how people first skim the document, identify relevant parts, and carefully read these parts to produce an answer, we combine a coarse, fast model for selecting relevant sentences and a more expensive RNN for producing the answer from those sentences. We treat sentence selection as a latent variable trained jointly from the answer only using reinforcement learning. Experiments demonstrate the state of the art performance on a challenging subset of the Wikireading and on a new dataset, while speeding up the model by 3.5x-6.7x.

##### Abstract (translated by Google)
我们提出了一个问题解答框架，可以有效地扩展到更长的文档，同时保持甚至提高最先进的模型的性能。虽然大多数成功的阅读理解方法依赖于递归神经网络（RNN），但是在长文档上运行它们的速度过于缓慢，因为很难在序列上并行化。受到人们第一次浏览文档，识别相关部分，仔细阅读这些部分以得出答案的启发，我们结合了一个粗糙的，快速的模型来选择相关的句子和一个更昂贵的RNN来从这些句子中产生答案。我们把句子选择作为一个潜在的变量，只用强化学习的答案来共同训练。实验展示了Wikireading中具有挑战性的子集和新数据集的最新性能，同时将模型速度提高了3.5x-6.7x。

##### URL
[https://arxiv.org/abs/1611.01839](https://arxiv.org/abs/1611.01839)

##### PDF
[https://arxiv.org/pdf/1611.01839](https://arxiv.org/pdf/1611.01839)

