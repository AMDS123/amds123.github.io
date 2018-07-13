---
layout: post
title: "Adding Attentiveness to the Neurons in Recurrent Neural Networks"
date: 2018-07-12 06:59:36
categories: arXiv_CV
tags: arXiv_CV Attention Action_Recognition RNN Recognition
author: Pengfei Zhang, Jianru Xue, Cuiling Lan, Wenjun Zeng, Zhanning Gao, Nanning Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) are capable of modeling the temporal dynamics of complex sequential information. However, the structures of existing RNN neurons mainly focus on controlling the contributions of current and historical information but do not explore the different importance levels of different elements in an input vector of a time slot. We propose adding a simple yet effective Element-wiseAttention Gate (EleAttG) to an RNN block (e.g., all RNN neurons in a network layer) that empowers the RNN neurons to have the attentiveness capability. For an RNN block, an EleAttG is added to adaptively modulate the input by assigning different levels of importance, i.e., attention, to each element/dimension of the input. We refer to an RNN block equipped with an EleAttG as an EleAtt-RNN block. Specifically, the modulation of the input is content adaptive and is performed at fine granularity, being element-wise rather than input-wise. The proposed EleAttG, as an additional fundamental unit, is general and can be applied to any RNN structures, e.g., standard RNN, Long Short-Term Memory (LSTM), or Gated Recurrent Unit (GRU). We demonstrate the effectiveness of the proposed EleAtt-RNN by applying it to the action recognition tasks on both 3D human skeleton data and RGB videos. Experiments show that adding attentiveness through EleAttGs to RNN blocks significantly boosts the power of RNNs.

##### Abstract (translated by Google)
递归神经网络（RNN）能够对复杂顺序信息的时间动态建模。然而，现有RNN神经元的结构主要集中在控制当前和历史信息的贡献，而没有探索时隙的输入向量中不同元素的不同重要性级别。我们建议将一个简单但有效的元素智能关注门（EleAttG）添加到RNN块（例如，网络层中的所有RNN神经元），其赋予RNN神经元具有注意力能力。对于RNN块，添加EleAttG以通过向输入的每个元素/维度分配不同的重要性级别（即，注意力）来自适应地调制输入。我们将配备有EleAttG的RNN块称为EleAtt-RNN块。具体地，输入的调制是内容自适应的并且以细粒度执行，是元素而不是输入。所提出的EleAttG作为附加的基本单元是通用的，并且可以应用于任何RNN结构，例如标准RNN，长短期存储器（LSTM）或门控循环单元（GRU）。我们通过将其应用于3D人体骨骼数据和RGB视频的动作识别任务来证明所提出的EleAtt-RNN的有效性。实验表明，通过EleAttGs对RNN块增加注意力可以显着提高RNN的功效。

##### URL
[http://arxiv.org/abs/1807.04445](http://arxiv.org/abs/1807.04445)

##### PDF
[http://arxiv.org/pdf/1807.04445](http://arxiv.org/pdf/1807.04445)

