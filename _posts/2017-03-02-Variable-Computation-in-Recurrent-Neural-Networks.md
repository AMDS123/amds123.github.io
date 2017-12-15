---
layout: post
title: "Variable Computation in Recurrent Neural Networks"
date: 2017-03-02 19:47:59
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention RNN
author: Yacine Jernite, Edouard Grave, Armand Joulin, Tomas Mikolov
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) have been used extensively and with increasing success to model various types of sequential data. Much of this progress has been achieved through devising recurrent units and architectures with the flexibility to capture complex statistics in the data, such as long range dependency or localized attention phenomena. However, while many sequential data (such as video, speech or language) can have highly variable information flow, most recurrent models still consume input features at a constant rate and perform a constant number of computations per time step, which can be detrimental to both speed and model capacity. In this paper, we explore a modification to existing recurrent units which allows them to learn to vary the amount of computation they perform at each step, without prior knowledge of the sequence's time structure. We show experimentally that not only do our models require fewer operations, they also lead to better performance overall on evaluation tasks.

##### Abstract (translated by Google)
递归神经网络（RNN）已经被广泛地使用，并且越来越成功地模拟各种类型的顺序数据。这些进展大部分是通过设计经常性的单位和体系结构，以灵活地捕捉数据中复杂的统计数据，例如远距离依赖或局部注意现象来实现的。然而，尽管许多顺序数据（例如视频，语音或语言）可以具有高度可变的信息流，但是大多数经常性模型仍然以恒定的速率消耗输入特征，并且每个时间步骤执行恒定数量的计算，这对两者都是有害的速度和模型的能力。在本文中，我们探索对现有经常性单位的修改，使他们能够学习改变他们在每一步执行的计算量，而不需要事先知道序列的时间结构。我们通过实验显示，不仅我们的模型需要更少的操作，而且还会导致评估任务的整体性能更好。

##### URL
[https://arxiv.org/abs/1611.06188](https://arxiv.org/abs/1611.06188)

##### PDF
[https://arxiv.org/pdf/1611.06188](https://arxiv.org/pdf/1611.06188)

