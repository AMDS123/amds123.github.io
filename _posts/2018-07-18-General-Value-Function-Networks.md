---
layout: post
title: "General Value Function Networks"
date: 2018-07-18 03:51:08
categories: arXiv_AI
tags: arXiv_AI RNN Prediction
author: Matthew Schlegel, Adam White, Andrew Patterson, Martha White
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we show that restricting the representation-layer of a Recurrent Neural Network (RNN) improves accuracy and reduces the depth of recursive training procedures in partially observable domains. Artificial Neural Networks have been shown to learn useful state representations for high-dimensional visual and continuous control domains. If the the tasks at hand exhibits long depends back in time, these instantaneous feed-forward approaches are augmented with recurrent connections and trained with Back-prop Through Time (BPTT). This unrolled training can become computationally prohibitive if the dependency structure is long, and while recent work on LSTMs and GRUs has improved upon naive training strategies, there is still room for improvements in computational efficiency and parameter sensitivity. In this paper we explore a simple modification to the classic RNN structure: restricting the state to be comprised of multi-step General Value Function predictions. We formulate an architecture called General Value Function Networks (GVFNs), and corresponding objective that generalizes beyond previous approaches. We show that our GVFNs are significantly more robust to train, and facilitate accurate prediction with no gradients needed back-in-time in domains with substantial long-term dependences.

##### Abstract (translated by Google)
在本文中，我们展示限制递归神经网络（RNN）的表示层提高了准确性并减少了部分可观察域中的递归训练过程的深度。人工神经网络已被证明可以学习高维视觉和连续控制域的有用状态表示。如果手头的任务表现出很长的时间取决于时间，那么这些瞬时前馈方法会通过循环连接得到增强，并通过反向穿越时间（BPTT）进行训练。如果依赖结构很长，则这种展开的训练可能在计算上变得过高，并且尽管最近关于LSTM和GRU的工作在初始训练策略上有所改进，但仍然存在改进计算效率和参数灵敏度的空间。在本文中，我们探索了对经典RNN结构的简单修改：将状态限制为由多步一般值函数预测组成。我们制定了一种称为通用价值功能网络（GVFN）的架构，以及超越以往方法的相应目标。我们表明，我们的GVFN对于训练具有更强的鲁棒性，并且有助于准确预测，在具有长期依赖性的域中不需要回溯所需的梯度。

##### URL
[https://arxiv.org/abs/1807.06763](https://arxiv.org/abs/1807.06763)

##### PDF
[https://arxiv.org/pdf/1807.06763](https://arxiv.org/pdf/1807.06763)

