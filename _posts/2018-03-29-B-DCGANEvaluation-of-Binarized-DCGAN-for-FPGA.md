---
layout: post
title: "B-DCGAN:Evaluation of Binarized DCGAN for FPGA"
date: 2018-03-29 05:43:23
categories: arXiv_CV
tags: arXiv_CV GAN CNN Deep_Learning
author: Hideo Terada, Hayaru Shouno
mathjax: true
---

* content
{:toc}

##### Abstract
We are trying to implement deep neural networks in the edge computing environment for real-world applications such as the IoT(Internet of Things), the FinTech etc., for the purpose of utilizing the significant achievement of Deep Learning in recent years. Especially, we now focus algorithm implementation on FPGA, because FPGA is one of the promising devices for low-cost and low-power implementation of the edge computer. In this work, we introduce Binary-DCGAN(B-DCGAN) - Deep Convolutional GAN model with binary weights and activations, and with using integer-valued operations in forward pass(train-time and run-time). And we show how to implement B-DCGAN on FPGA(Xilinx Zynq). Using the B-DCGAN, we do feasibility study of FPGA's characteristic and performance for Deep Learning. Because the binarization and using integer-valued operation reduce the memory capacity and the number of the circuit gates, it is very effective for FPGA implementation. On the other hand, the quality of generated data from the model will be decreased by these reductions. So we investigate the influence of these reductions.

##### Abstract (translated by Google)
为了利用近年来深度学习的重大成果，我们试图在边缘计算环境中实现深度神经网络，以实现物联网（IoT），金融科技等实际应用。特别是，我们现在把重点放在FPGA的实现上，因为FPGA是边缘计算机低成本和低功耗实现的有前途的设备之一。在这项工作中，我们引入Binary-DCGAN（B-DCGAN） - 具有二进制权重和激活的深度卷积GAN模型，以及在正向通过（列车时间和运行时间）中使用整数值运算。我们将演示如何在FPGA上实现B-DCGAN（Xilinx Zynq）。使用B-DCGAN，我们对深度学习的FPGA特性和性能进行可行性研究。由于二进制化和使用整数值操作减少了存储器容量和电路门数，因此它对于FPGA的实现非常有效。另一方面，模型生成的数据质量会因这些降低而减少。所以我们调查这些减少的影响。

##### URL
[http://arxiv.org/abs/1803.10930](http://arxiv.org/abs/1803.10930)

##### PDF
[http://arxiv.org/pdf/1803.10930](http://arxiv.org/pdf/1803.10930)

