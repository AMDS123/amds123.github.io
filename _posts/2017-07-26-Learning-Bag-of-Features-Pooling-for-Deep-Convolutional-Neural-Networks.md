---
layout: post
title: "Learning Bag-of-Features Pooling for Deep Convolutional Neural Networks"
date: 2017-07-26 04:25:06
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Nikolaos Passalis, Anastasios Tefas
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) are well established models capable of achieving state-of-the-art classification accuracy for various computer vision tasks. However, they are becoming increasingly larger, using millions of parameters, while they are restricted to handling images of fixed size. In this paper, a quantization-based approach, inspired from the well-known Bag-of-Features model, is proposed to overcome these limitations. The proposed approach, called Convolutional BoF (CBoF), uses RBF neurons to quantize the information extracted from the convolutional layers and it is able to natively classify images of various sizes as well as to significantly reduce the number of parameters in the network. In contrast to other global pooling operators and CNN compression techniques the proposed method utilizes a trainable pooling layer that it is end-to-end differentiable, allowing the network to be trained using regular back-propagation and to achieve greater distribution shift invariance than competitive methods. The ability of the proposed method to reduce the parameters of the network and increase the classification accuracy over other state-of-the-art techniques is demonstrated using three image datasets.

##### Abstract (translated by Google)
卷积神经网络（CNN）是能够为各种计算机视觉任务实现最先进的分类精度的完善的模型。然而，他们正在变得越来越大，使用数百万个参数，而他们被限制在处理固定大小的图像。在本文中，提出了一个基于量化的方法，从众所周知的袋特征模型启发，以克服这些限制。所提出的方法称为卷积BoF（CBoF），它使用RBF神经元来量化从卷积层提取的信息，并且能够自然地对各种尺寸的图像进行分类，并且显着减少网络中的参数数量。与其他全球联营运营商和CNN压缩技术相比，所提出的方法利用可训练的汇聚层，该汇聚层是端到端的可微分的，使得网络可以使用常规的反向传播进行训练，并且实现比竞争方法更大的分布移位不变性。使用三个图像数据集证明了所提出的方法降低网络参数的能力，并提高了与其他现有技术的分类精度。

##### URL
[https://arxiv.org/abs/1707.08105](https://arxiv.org/abs/1707.08105)

##### PDF
[https://arxiv.org/pdf/1707.08105](https://arxiv.org/pdf/1707.08105)

