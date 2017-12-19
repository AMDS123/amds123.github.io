---
layout: post
title: "Differential Recurrent Neural Networks for Action Recognition"
date: 2015-04-25 03:59:14
categories: arXiv_CV
tags: arXiv_CV Salient Action_Recognition RNN Recognition
author: Vivek Veeriah, Naifan Zhuang, Guo-Jun Qi
mathjax: true
---

* content
{:toc}

##### Abstract
The long short-term memory (LSTM) neural network is capable of processing complex sequential information since it utilizes special gating schemes for learning representations from long input sequences. It has the potential to model any sequential time-series data, where the current hidden state has to be considered in the context of the past hidden states. This property makes LSTM an ideal choice to learn the complex dynamics of various actions. Unfortunately, the conventional LSTMs do not consider the impact of spatio-temporal dynamics corresponding to the given salient motion patterns, when they gate the information that ought to be memorized through time. To address this problem, we propose a differential gating scheme for the LSTM neural network, which emphasizes on the change in information gain caused by the salient motions between the successive frames. This change in information gain is quantified by Derivative of States (DoS), and thus the proposed LSTM model is termed as differential Recurrent Neural Network (dRNN). We demonstrate the effectiveness of the proposed model by automatically recognizing actions from the real-world 2D and 3D human action datasets. Our study is one of the first works towards demonstrating the potential of learning complex time-series representations via high-order derivatives of states.

##### Abstract (translated by Google)
长期短期记忆（LSTM）神经网络能够处理复杂的时序信息，因为它利用特殊的门控方案来学习长输入序列的表示。它有可能模拟任何连续的时间序列数据，其中当前隐藏状态必须在过去隐藏状态的背景下考虑。这个属性使得LSTM成为学习各种动作的复杂动力的理想选择。不幸的是，传统的LSTMs没有考虑到与给定的显着运动模式相对应的时空动态的影响，当他们选择应该记住的信息时间。为了解决这个问题，我们提出了一个LSTM神经网络的差分门控方案，它强调了连续帧之间的显着运动引起的信息增益的变化。信息增益的这种变化是通过状态导数（DoS）量化的，因此所提出的LSTM模型被称为差分递归神经网络（dRNN）。我们通过自动识别来自现实世界的二维和三维人类活动数据集的行为来证明所提出模型的有效性。我们的研究是通过状态的高阶导数来展示学习复杂时间序列表示的潜力的第一批作品之一。

##### URL
[https://arxiv.org/abs/1504.06678](https://arxiv.org/abs/1504.06678)

##### PDF
[https://arxiv.org/pdf/1504.06678](https://arxiv.org/pdf/1504.06678)

