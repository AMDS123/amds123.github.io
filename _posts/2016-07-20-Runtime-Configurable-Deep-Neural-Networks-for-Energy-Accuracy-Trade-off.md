---
layout: post
title: "Runtime Configurable Deep Neural Networks for Energy-Accuracy Trade-off"
date: 2016-07-20 20:42:51
categories: arXiv_CV
tags: arXiv_CV
author: Hokchhay Tann, Soheil Hashemi, R. Iris Bahar, Sherief Reda
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel dynamic configuration technique for deep neural networks that permits step-wise energy-accuracy trade-offs during runtime. Our configuration technique adjusts the number of channels in the network dynamically depending on response time, power, and accuracy targets. To enable this dynamic configuration technique, we co-design a new training algorithm, where the network is incrementally trained such that the weights in channels trained in earlier steps are fixed. Our technique provides the flexibility of multiple networks while storing and utilizing one set of weights. We evaluate our techniques using both an ASIC-based hardware accelerator as well as a low-power embedded GPGPU and show that our approach leads to only a small or negligible loss in the final network accuracy. We analyze the performance of our proposed methodology using three well-known networks for MNIST, CIFAR-10, and SVHN datasets, and we show that we are able to achieve up to 95% energy reduction with less than 1% accuracy loss across the three benchmarks. In addition, compared to prior work on dynamic network reconfiguration, we show that our approach leads to approximately 50% savings in storage requirements, while achieving similar accuracy.

##### Abstract (translated by Google)
我们提出了一个深度神经网络的新型动态配置技术，允许在运行期间逐步进行能量精度折衷。我们的配置技术根据响应时间，功耗和准确度目标动态调整网络中的通道数量。为了实现这种动态配置技术，我们合作设计了一种新的训练算法，其中对网络进行增量训练，使得前面步骤训练的信道中的权重是固定的。我们的技术提供了多个网络的灵活性，同时存储和利用一组权重。我们使用基于ASIC的硬件加速器以及低功耗嵌入式GPGPU评估我们的技术，并显示我们的方法仅导致最终网络精度的损失很小或可以忽略不计。我们使用MNIST，CIFAR-10和SVHN数据集的三个知名网络分析了我们提出的方法的性能，结果表明我们能够实现高达95％的能量减少，精度损失小于1％基准。另外，与以前的动态网络重新配置相比，我们发现我们的方法可以节约大约50％的存储需求，同时达到相似的精度。

##### URL
[https://arxiv.org/abs/1607.05418](https://arxiv.org/abs/1607.05418)

##### PDF
[https://arxiv.org/pdf/1607.05418](https://arxiv.org/pdf/1607.05418)

