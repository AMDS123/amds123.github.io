---
layout: post
title: "Hardware-Driven Nonlinear Activation for Stochastic Computing Based Deep Convolutional Neural Networks"
date: 2017-03-12 15:27:23
categories: arXiv_CV
tags: arXiv_CV CNN
author: Ji Li, Zihao Yuan, Zhe Li, Caiwen Ding, Ao Ren, Qinru Qiu, Jeffrey Draper, Yanzhi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, Deep Convolutional Neural Networks (DCNNs) have made unprecedented progress, achieving the accuracy close to, or even better than human-level perception in various tasks. There is a timely need to map the latest software DCNNs to application-specific hardware, in order to achieve orders of magnitude improvement in performance, energy efficiency and compactness. Stochastic Computing (SC), as a low-cost alternative to the conventional binary computing paradigm, has the potential to enable massively parallel and highly scalable hardware implementation of DCNNs. One major challenge in SC based DCNNs is designing accurate nonlinear activation functions, which have a significant impact on the network-level accuracy but cannot be implemented accurately by existing SC computing blocks. In this paper, we design and optimize SC based neurons, and we propose highly accurate activation designs for the three most frequently used activation functions in software DCNNs, i.e, hyperbolic tangent, logistic, and rectified linear units. Experimental results on LeNet-5 using MNIST dataset demonstrate that compared with a binary ASIC hardware DCNN, the DCNN with the proposed SC neurons can achieve up to 61X, 151X, and 2X improvement in terms of area, power, and energy, respectively, at the cost of small precision degradation.In addition, the SC approach achieves up to 21X and 41X of the area, 41X and 72X of the power, and 198200X and 96443X of the energy, compared with CPU and GPU approaches, respectively, while the error is increased by less than 3.07%. ReLU activation is suggested for future SC based DCNNs considering its superior performance under a small bit stream length.

##### Abstract (translated by Google)
最近，深度卷积神经网络（DCNNs）取得了前所未有的进步，在各种任务中达到接近或甚至优于人类感知的准确度。及时需要将最新的软件DCNN映射到特定应用的硬件，以便在性能，能源效率和紧凑性方面实现数量级的提高。随机计算（SC）作为传统二进制计算范例的低成本替代方案，有可能实现DCNN的大规模并行和高度可扩展的硬件实现。基于SC的DCNNs面临的一个主要挑战是设计精确的非线性激活函数，这对网络级精度有显着的影响，但不能被现有的SC计算模块精确地实现。在本文中，我们设计并优化了基于SC的神经元，并且我们为软件DCNN中三个最常用的激活函数提出了高度准确的激活设计，即双曲正切，逻辑和整流线性单元。在使用MNIST数据集的LeNet-5上的实验结果表明，与二进制ASIC硬件DCNN相比，具有提议的SC神经元的DCNN在面积，功率和能量方面分别可以达到61X，151X和2X的改善降低了精度降低的代价。另外，与CPU和GPU方法相比，SC方法分别实现了高达21X和41X的面积，41X和72X的功耗，以及198200X和96443X的能量，而误差增幅小于3.07％。考虑到其在小比特流长度下的优越性能，建议将来基于SC的DCNN的ReLU激活。

##### URL
[https://arxiv.org/abs/1703.04135](https://arxiv.org/abs/1703.04135)

##### PDF
[https://arxiv.org/pdf/1703.04135](https://arxiv.org/pdf/1703.04135)

