---
layout: post
title: "Neural Network-Based Dynamic Threshold Detection for Non-Volatile Memories"
date: 2019-02-17 16:51:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge RNN Detection
author: Zhen Mei, Kui Cai, Xingwei Zhong
mathjax: true
---

* content
{:toc}

##### Abstract
The memory physics induced unknown offset of the channel is a critical and difficult issue to be tackled for many non-volatile memories (NVMs). In this paper, we first propose novel neural network (NN) detectors by using the multilayer perceptron (MLP) network and the recurrent neural network (RNN), which can effectively tackle the unknown offset of the channel. However, compared with the conventional threshold detector, the NN detectors will incur a significant delay of the read latency and more power consumption. Therefore, we further propose a novel dynamic threshold detector (DTD), whose detection threshold can be derived based on the outputs of the proposed NN detectors. In this way, the NN-based detection only needs to be invoked when the error correction code (ECC) decoder fails, or periodically when the system is in the idle state. Thereafter, the threshold detector will still be adopted by using the adjusted detection threshold derived base on the outputs of the NN detector, until a further adjustment of the detection threshold is needed. Simulation results demonstrate that the proposed DTD based on the RNN detection can achieve the error performance of the optimum detector, without the prior knowledge of the channel.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1902.06289](https://arxiv.org/abs/1902.06289)

##### PDF
[https://arxiv.org/pdf/1902.06289](https://arxiv.org/pdf/1902.06289)

