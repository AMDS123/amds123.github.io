---
layout: post
title: "BitSplit-Net: Multi-bit Deep Neural Network with Bitwise Activation Function"
date: 2019-03-23 11:52:23
categories: arXiv_CV
tags: arXiv_CV Classification
author: Hyungjun Kim, Yulhwa Kim, Sungju Ryu, Jae-Joon Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Significant computational cost and memory requirements for deep neural networks (DNNs) make it difficult to utilize DNNs in resource-constrained environments. Binary neural network (BNN), which uses binary weights and binary activations, has been gaining interests for its hardware-friendly characteristics and minimal resource requirement. However, BNN usually suffers from accuracy degradation. In this paper, we introduce "BitSplit-Net", a neural network which maintains the hardware-friendly characteristics of BNN while improving accuracy by using multi-bit precision. In BitSplit-Net, each bit of multi-bit activations propagates independently throughout the network before being merged at the end of the network. Thus, each bit path of the BitSplit-Net resembles BNN and hardware friendly features of BNN, such as bitwise binary activation function, are preserved in our scheme. We demonstrate that the BitSplit version of LeNet-5, VGG-9, AlexNet, and ResNet-18 can be trained to have similar classification accuracy at a lower computational cost compared to conventional multi-bit networks with low bit precision (&lt;= 4-bit). We further evaluate BitSplit-Net on GPU with custom CUDA kernel, showing that BitSplit-Net can achieve better hardware performance in comparison to conventional multi-bit networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09807](http://arxiv.org/abs/1903.09807)

##### PDF
[http://arxiv.org/pdf/1903.09807](http://arxiv.org/pdf/1903.09807)

