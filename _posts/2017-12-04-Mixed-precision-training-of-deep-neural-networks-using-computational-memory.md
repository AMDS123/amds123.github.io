---
layout: post
title: "Mixed-precision training of deep neural networks using computational memory"
date: 2017-12-04 16:54:12
categories: arXiv_CV
tags: arXiv_CV GAN Speech_Recognition Classification Recognition
author: Nandakumar S. R., Manuel Le Gallo, Irem Boybat, Bipin Rajendran, Abu Sebastian, Evangelos Eleftheriou
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have revolutionized the field of machine learning by providing unprecedented human-like performance in solving many real-world problems such as image and speech recognition. Training of large DNNs, however, is a computationally intensive task, and this necessitates the development of novel computing architectures targeting this application. A computational memory unit where resistive memory devices are organized in crossbar arrays can be used to locally store the synaptic weights in their conductance states. The expensive multiply accumulate operations can be performed in place using Kirchhoff's circuit laws in a non-von Neumann manner. However, a key challenge remains the inability to alter the conductance states of the devices in a reliable manner during the weight update process. We propose a mixed-precision architecture that combines a computational memory unit storing the synaptic weights with a digital processing unit and an additional memory unit accumulating weight updates in high precision. The new architecture delivers classification accuracies comparable to those of floating-point implementations without being constrained by challenges associated with the non-ideal weight update characteristics of emerging resistive memories. A two layer neural network in which the computational memory unit is realized using non-linear stochastic models of phase-change memory devices achieves a test accuracy of 97.40% on the MNIST handwritten digit classification problem.

##### Abstract (translated by Google)
深度神经网络通过在解决诸如图像和语音识别等许多现实问题中提供前所未有的类人表现，彻底改变了机器学习领域。但是，对大型DNN的培训是一项计算密集型任务，因此需要开发针对此应用的新型计算架构。其中电阻式存储器装置以纵横排列组织的计算存储器单元可用于局部存储突触权重在其电导状态中。昂贵的乘法累加操作可以使用基尔霍夫电路定律以非冯诺依曼方式进行。然而，重要的挑战仍然是在重量更新过程中无法可靠地改变设备的电导状态。我们提出了一个混合精度架构，将存储突触权重的计算存储器单元与数字处理单元和附加的存储器单元进行高精度累加重量更新。新架构提供的分类精度可与浮点实现相媲美，而不受与新兴电阻式存储器的非理想重量更新特性相关的挑战的限制。采用相变存储器非线性随机模型实现计算存储单元的双层神经网络在MNIST手写数字分类问题上的测试精度达到了97.40％。

##### URL
[https://arxiv.org/abs/1712.01192](https://arxiv.org/abs/1712.01192)

##### PDF
[https://arxiv.org/pdf/1712.01192](https://arxiv.org/pdf/1712.01192)

