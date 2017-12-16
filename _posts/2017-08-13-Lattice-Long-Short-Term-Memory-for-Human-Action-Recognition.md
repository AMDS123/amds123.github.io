---
layout: post
title: "Lattice Long Short-Term Memory for Human Action Recognition"
date: 2017-08-13 19:27:34
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN RNN Recognition
author: Lin Sun, Kui Jia, Kevin Chen, Dit Yan Yeung, Bertram E. Shi, Silvio Savarese
mathjax: true
---

* content
{:toc}

##### Abstract
Human actions captured in video sequences are three-dimensional signals characterizing visual appearance and motion dynamics. To learn action patterns, existing methods adopt Convolutional and/or Recurrent Neural Networks (CNNs and RNNs). CNN based methods are effective in learning spatial appearances, but are limited in modeling long-term motion dynamics. RNNs, especially Long Short-Term Memory (LSTM), are able to learn temporal motion dynamics. However, naively applying RNNs to video sequences in a convolutional manner implicitly assumes that motions in videos are stationary across different spatial locations. This assumption is valid for short-term motions but invalid when the duration of the motion is long. In this work, we propose Lattice-LSTM (L2STM), which extends LSTM by learning independent hidden state transitions of memory cells for individual spatial locations. This method effectively enhances the ability to model dynamics across time and addresses the non-stationary issue of long-term motion dynamics without significantly increasing the model complexity. Additionally, we introduce a novel multi-modal training procedure for training our network. Unlike traditional two-stream architectures which use RGB and optical flow information as input, our two-stream model leverages both modalities to jointly train both input gates and both forget gates in the network rather than treating the two streams as separate entities with no information about the other. We apply this end-to-end system to benchmark datasets (UCF-101 and HMDB-51) of human action recognition. Experiments show that on both datasets, our proposed method outperforms all existing ones that are based on LSTM and/or CNNs of similar model complexities.

##### Abstract (translated by Google)
在视频序列中捕获的人类行为是表征视觉外观和动作动态的三维信号。为了学习行动模式，现有的方法采用卷积和/或递归神经网络（CNN和RNN）。基于CNN的方法在学习空间外观方面是有效的，但在建模长期运动动力学方面受到限制。 RNN，尤其是长时间短时记忆（LSTM）能够学习时间动态。然而，以卷积方式天真地将RNN应用于视频序列隐含地假定视频中的运动在不同的空间位置上是静止的。这个假设对于短期运动是有效的，但是当运动持续时间很长时是无效的。在这项工作中，我们提出了Lattice-LSTM（L2STM），它通过学习单个空间位置的存储单元的独立隐藏状态转换来扩展LSTM。这种方法有效地增强了动态建模的能力，解决了长期运动动态的非平稳问题，而不会显着增加模型的复杂性。另外，我们引入了一个新的多模态训练程序来训练我们的网络。与使用RGB和光流信息作为输入的传统双流体系结构不同，我们的双流模型利用两种模式共同训练输入门和网络中的两个忘记门，而不是将两个流视为分离的实体，另一个。我们将这个端到端系统应用于人类行为识别的基准数据集（UCF-101和HMDB-51）。实验表明，在两个数据集上，我们提出的方法都优于现有的基于类似模型复杂度的LSTM和/或CNNs的方法。

##### URL
[https://arxiv.org/abs/1708.03958](https://arxiv.org/abs/1708.03958)

##### PDF
[https://arxiv.org/pdf/1708.03958](https://arxiv.org/pdf/1708.03958)

