---
layout: post
title: "Skip RNN: Learning to Skip State Updates in Recurrent Neural Networks"
date: 2018-02-05 17:14:12
categories: arXiv_AI
tags: arXiv_AI Face Inference RNN
author: Victor Campos, Brendan Jou, Xavier Giro-i-Nieto, Jordi Torres, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks (RNNs) continue to show outstanding performance in sequence modeling tasks. However, training RNNs on long sequences often face challenges like slow inference, vanishing gradients and difficulty in capturing long term dependencies. In backpropagation through time settings, these issues are tightly coupled with the large, sequential computational graph resulting from unfolding the RNN in time. We introduce the Skip RNN model which extends existing RNN models by learning to skip state updates and shortens the effective size of the computational graph. This model can also be encouraged to perform fewer state updates through a budget constraint. We evaluate the proposed model on various tasks and show how it can reduce the number of required RNN updates while preserving, and sometimes even improving, the performance of the baseline RNN models. Source code is publicly available at https://imatge-upc.github.io/skiprnn-2017-telecombcn/ .

##### Abstract (translated by Google)
递归神经网络（RNN）在序列建模任务中继续表现出色。然而，对长序列进行RNN训练往往面临诸如缓慢推理，消失梯度和难以捕获长期依赖性等挑战。在通过时间设置的反向传播中，这些问题与通过及时展开RNN而产生的大的顺序计算图紧密耦合。我们引入了Skip RNN模型，它通过学习跳过状态更新来扩展现有的RNN模型，缩短了计算图的有效大小。也可以鼓励这种模式通过预算约束执行更少的状态更新。我们评估所提出的各种任务模型，并说明如何减少所需的RNN更新次数，同时保留甚至改进基线RNN模型的性能。源代码可在https://imatge-upc.github.io/skiprnn-2017-telecombcn/上公开获取。

##### URL
[http://arxiv.org/abs/1708.06834](http://arxiv.org/abs/1708.06834)

##### PDF
[http://arxiv.org/pdf/1708.06834](http://arxiv.org/pdf/1708.06834)

