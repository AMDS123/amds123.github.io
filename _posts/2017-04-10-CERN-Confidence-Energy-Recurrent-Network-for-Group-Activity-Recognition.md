---
layout: post
title: "CERN: Confidence-Energy Recurrent Network for Group Activity Recognition"
date: 2017-04-10 21:08:39
categories: arXiv_CV
tags: arXiv_CV RNN Prediction Recognition
author: Tianmin Shu, Sinisa Todorovic, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
This work is about recognizing human activities occurring in videos at distinct semantic levels, including individual actions, interactions, and group activities. The recognition is realized using a two-level hierarchy of Long Short-Term Memory (LSTM) networks, forming a feed-forward deep architecture, which can be trained end-to-end. In comparison with existing architectures of LSTMs, we make two key contributions giving the name to our approach as Confidence-Energy Recurrent Network -- CERN. First, instead of using the common softmax layer for prediction, we specify a novel energy layer (EL) for estimating the energy of our predictions. Second, rather than finding the common minimum-energy class assignment, which may be numerically unstable under uncertainty, we specify that the EL additionally computes the p-values of the solutions, and in this way estimates the most confident energy minimum. The evaluation on the Collective Activity and Volleyball datasets demonstrates: (i) advantages of our two contributions relative to the common softmax and energy-minimization formulations and (ii) a superior performance relative to the state-of-the-art approaches.

##### Abstract (translated by Google)
这项工作是关于识别不同语义层次的视频中发生的人类活动，包括个人行为，互动和小组活动。使用长期短期记忆（LSTM）网络的两级分层结构来实现识别，形成前端深层架构，可以进行端到端的训练。与现有的LSTM架构相比，我们做了两个重要的贡献，我们的名称为我们的方法作为置信能量递归网络 -  CERN。首先，我们指定一个新的能量层（EL）来估计我们预测的能量，而不是使用普通的softmax层进行预测。其次，我们没有找到共同的最小能量等级分配，这在不确定的情况下在数值上可能是不稳定的，而是指定EL额外计算解的p值，并以这种方式估计最自信的能量最小值。对集体活动和排球数据集的评估表明：（i）我们的两个贡献相对于常见的softmax和能量最小化配方的优点，和（ii）相对于最先进的方法的优越性能。

##### URL
[https://arxiv.org/abs/1704.03058](https://arxiv.org/abs/1704.03058)

##### PDF
[https://arxiv.org/pdf/1704.03058](https://arxiv.org/pdf/1704.03058)

