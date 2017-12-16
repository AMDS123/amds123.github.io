---
layout: post
title: "TensorQuant - A Simulation Toolbox for Deep Neural Network Quantization"
date: 2017-10-13 10:15:27
categories: arXiv_CV
tags: arXiv_CV Inference
author: Dominik Marek Loroch, Norbert Wehn, Franz-Josef Pfreundt, Janis Keuper
mathjax: true
---

* content
{:toc}

##### Abstract
Recent research implies that training and inference of deep neural networks (DNN) can be computed with low precision numerical representations of the training/test data, weights and gradients without a general loss in accuracy. The benefit of such compact representations is twofold: they allow a significant reduction of the communication bottleneck in distributed DNN training and faster neural network implementations on hardware accelerators like FPGAs. Several quantization methods have been proposed to map the original 32-bit floating point problem to low-bit representations. While most related publications validate the proposed approach on a single DNN topology, it appears to be evident, that the optimal choice of the quantization method and number of coding bits is topology dependent. To this end, there is no general theory available, which would allow users to derive the optimal quantization during the design of a DNN topology. In this paper, we present a quantization tool box for the TensorFlow framework. TensorQuant allows a transparent quantization simulation of existing DNN topologies during training and inference. TensorQuant supports generic quantization methods and allows experimental evaluation of the impact of the quantization on single layers as well as on the full topology. In a first series of experiments with TensorQuant, we show an analysis of fix-point quantizations of popular CNN topologies.

##### Abstract (translated by Google)
最近的研究表明，深度神经网络（DNN）的训练和推理可以通过训练/测试数据的低精度数字表示，权重和梯度来计算，而不会降低准确性。这种紧凑的表示的好处是双重的：它们可以显着减少分布式DNN训练中的通信瓶颈，以及像FPGA这样的硬件加速器上更快的神经网络实现。已经提出了几种量化方法将原始的32位浮点问题映射为低位表示。虽然大多数相关的出版物在单个DNN拓扑上验证了所提出的方法，但看起来很明显，量化方法的最佳选择和编码比特的数量是与拓扑有关的。为此，没有可用的一般理论，这将允许用户在DNN拓扑的设计期间导出最佳量化。在本文中，我们提出了一个TensorFlow框架的量化工具箱。 TensorQuant允许在训练和推理期间对现有的DNN拓扑进行透明的量化模拟。 TensorQuant支持通用的量化方法，可以对量化对单层以及全拓扑的影响进行实验评估。在TensorQuant的第一个系列实验中，我们展示了流行的CNN拓扑的定点量化分析。

##### URL
[https://arxiv.org/abs/1710.05758](https://arxiv.org/abs/1710.05758)

##### PDF
[https://arxiv.org/pdf/1710.05758](https://arxiv.org/pdf/1710.05758)

