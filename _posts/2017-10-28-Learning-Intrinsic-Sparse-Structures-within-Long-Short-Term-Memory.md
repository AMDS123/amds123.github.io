---
layout: post
title: "Learning Intrinsic Sparse Structures within Long Short-Term Memory"
date: 2017-10-28 15:49:22
categories: arXiv_CL
tags: arXiv_CL Sparse RNN Language_Model
author: Wei Wen, Yuxiong He, Samyam Rajbhandari, Wenhan Wang, Fang Liu, Bin Hu, Yiran Chen, Hai Li
mathjax: true
---

* content
{:toc}

##### Abstract
Model compression is significant for the wide adoption of Recurrent Neural Networks (RNNs) in both user devices possessing limited resources and business clusters requiring quick responses to large-scale service requests. This work aims to learn structurally-sparse Long Short-Term Memory (LSTM) by reducing the sizes of basic structures within LSTM units, including input updates, gates, hidden states, cell states and outputs. Independently reducing the sizes of basic structures can result in inconsistent dimensions among them, and consequently, end up with invalid LSTM units. To overcome the problem, we propose Intrinsic Sparse Structures (ISS) in LSTMs. Removing a component of ISS will decrease the sizes of all basic structures by one simultaneously and thereby always maintain the dimension consistency. By learning ISS within LSTM units, the obtained LSTMs remain regular while having much smaller basic structures. Our method achieves 10.59x speedup in state-of-the-art LSTMs, without losing any perplexity of language modeling of Penn TreeBank dataset. It is also successfully evaluated through a compact model with only 2.69M weights for machine Question Answering of SQuAD dataset. Our source code is public available at this https URL

##### Abstract (translated by Google)
模型压缩对于在具有有限资源的用户设备和需要对大规模服务请求作出快速响应的业务群集中广泛采用递归神经网络（RNN）是重要的。这项工作旨在通过减少LSTM单位内的基本结构，包括输入更新，门，隐状态，电池状态和输出的大小，了解结构稀疏长短期记忆（LSTM）。独立地缩小基本结构的尺寸可能导致它们之间的尺寸不一致，从而导致无效的LSTM单元。为了克服这个问题，我们提出了LSTM中的本征稀疏结构（ISS）。移除ISS组件将会同时减小所有基本结构的尺寸，从而始终保持尺寸一致性。通过在LSTM单元内学习ISS，获得的LSTM保持规律，同时具有更小的基本结构。我们的方法在最先进的LSTM中实现了10.59倍的加速，而不会丢失Penn TreeBank数据集的语言建模的困惑。它也成功地通过一个紧凑的模型进行评估，只有2.69M重量的SQUAD数据集的机器问题答案。我们的源代码在此https网址上公开

##### URL
[https://arxiv.org/abs/1709.05027](https://arxiv.org/abs/1709.05027)

##### PDF
[https://arxiv.org/pdf/1709.05027](https://arxiv.org/pdf/1709.05027)

