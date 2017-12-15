---
layout: post
title: "Training Skinny Deep Neural Networks with Iterative Hard Thresholding Methods"
date: 2016-07-19 06:41:31
categories: arXiv_CV
tags: arXiv_CV Classification Recognition
author: Xiaojie Jin, Xiaotong Yuan, Jiashi Feng, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have achieved remarkable success in a wide range of practical problems. However, due to the inherent large parameter space, deep models are notoriously prone to overfitting and difficult to be deployed in portable devices with limited memory. In this paper, we propose an iterative hard thresholding (IHT) approach to train Skinny Deep Neural Networks (SDNNs). An SDNN has much fewer parameters yet can achieve competitive or even better performance than its full CNN counterpart. More concretely, the IHT approach trains an SDNN through following two alternative phases: (I) perform hard thresholding to drop connections with small activations and fine-tune the other significant filters; (II)~re-activate the frozen connections and train the entire network to improve its overall discriminative capability. We verify the superiority of SDNNs in terms of efficiency and classification performance on four benchmark object recognition datasets, including CIFAR-10, CIFAR-100, MNIST and ImageNet. Experimental results clearly demonstrate that IHT can be applied for training SDNN based on various CNN architectures such as NIN and AlexNet.

##### Abstract (translated by Google)
深度神经网络在广泛的实际问题中取得了显着的成功。然而，由于固有的较大的参数空间，深层模型出现容易过度拟合并且难以部署在具有有限存储器的便携式设备中。在本文中，我们提出了迭代硬阈值（IHT）方法来训练皮肤深度神经网络（SDNN）。一个SDNN参数少得多，可以达到比其完整CNN对应的竞争力甚至更好的性能。更具体地说，IHT方法通过以下两个备选阶段来训练SDNN：（I）执行硬阈值处理以断开小激活的连接并微调其他重要的过滤器; （二）重新激活冻结连接，对整个网络进行训练，提高整体判别能力。在CIFAR-10，CIFAR-100，MNIST和ImageNet四个基准目标识别数据集上，我们验证了SDNN在效率和分类性能方面的优越性。实验结果清楚地表明，IHT可以用于基于各种CNN体系结构（如NIN和AlexNet）的SDNN训练。

##### URL
[https://arxiv.org/abs/1607.05423](https://arxiv.org/abs/1607.05423)

##### PDF
[https://arxiv.org/pdf/1607.05423](https://arxiv.org/pdf/1607.05423)

