---
layout: post
title: "Budget-Aware Activity Detection with A Recurrent Policy Network"
date: 2017-11-30 21:52:27
categories: arXiv_CV
tags: arXiv_CV Detection
author: Behrooz Mahasseni, Xiaodong Yang, Pavlo Molchanov, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the challenging problem of effi- cient temporal activity detection in untrimmed long videos. While most recent work has focused and advanced the de- tection accuracy, the inference time can take seconds to minutes in processing one video, which is computationally prohibitive for many applications with tight runtime con- straints. This motivates our proposed budget-aware frame- work, which learns to perform activity detection by intel- ligently selecting a small subset of frames according to a specified time or computational budget. We formulate this problem as a Markov decision process, and adopt a recurrent network to model a policy for the frame selec- tion. To train the network, we employ a recurrent policy gradient approach to approximate the gradient of the non- decomposable and non-differentiable objective defined in our problem. In the extensive experiments on two bench- mark datasets, we achieve competitive detection accuracy, and more importantly, our approach is able to substantially reduce computational time and detect multiple activities in only 348ms for each untrimmed long video of THUMOS14 and ActivityNet.

##### Abstract (translated by Google)
在本文中，我们解决了未修剪的长视频中有效的时间活动检测的挑战性问题。尽管最近的工作集中并提高了检测精度，但在处理一个视频时，推理时间可能需要几秒到几分钟，对于许多运行时间受到限制的应用而言，这在计算上是禁止的。这激发了我们提出的预算意识框架，该框架通过智能地根据指定的时间或计算预算选择一小部分帧来学习执行活动检测。我们将这个问题作为一个马尔可夫决策过程来制定，并采用一个循环网络来模拟一个框架选择策略。为了训练网络，我们采用了一种反复的策略梯度方法来逼近我们的问题中定义的不可分解和不可微分目标的梯度。在两个基准数据集的广泛实验中，我们实现了有竞争力的检测精度，更重要的是，我们的方法能够显着减少计算时间，并且对于每个未修剪的THUMOS14和ActivityNet长视频，仅在348ms内检测多个活动。

##### URL
[https://arxiv.org/abs/1712.00097](https://arxiv.org/abs/1712.00097)

##### PDF
[https://arxiv.org/pdf/1712.00097](https://arxiv.org/pdf/1712.00097)

