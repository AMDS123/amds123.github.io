---
layout: post
title: "clcNet: Improving the Efficiency of Convolutional Neural Network using Channel Local Convolutions"
date: 2017-12-17 17:07:54
categories: arXiv_CV
tags: arXiv_CV CNN
author: Dong-Qing Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Depthwise convolution and grouped convolution has been successfully applied to improve the efficiency of convolutional neural network (CNN). This paper generalizes these convolution models to a general type of convolution named channel local convolution (CLC), where an output channel of convolution only depends on a subset of its input channels. This concept extends the spatial locality property of convolution to the channel dimension, thereby offering new dimension for network design. A CLC kernel is characterized by its channel dependency graph (CDG), the graphical representation of the dependencies between the input and output channels. CDG can be utilized to facilitate the design of the convolution block created by stacking multiple CLC kernels. We present an example of such design named CLC block, a novel structure distinct from previous models with fewer parameters and less computational cost. Based upon the CLC blocks, a new convolutional neural network named clcNet is constructed. And the experiments on Imagenet-1K dataset show that the clcNet achieves significantly higher computational efficiency and fewer parameters compared to the state-of-the-art networks.

##### Abstract (translated by Google)
深度卷积和分组卷积已成功应用于提高卷积神经网络（CNN）的效率。本文将这些卷积模型推广到通常称为信道本地卷积（CLC）的卷积类型，其中卷积的输出信道仅取决于其输入信道的子集。这个概念将卷积的空间局部性扩展到信道维度，从而为网络设计提供了新的维度。 CLC内核的特征在于其通道依赖图（CDG），即输入和输出通道之间依赖关系的图形表示。可以利用CDG来促进通过堆叠多个CLC内核而创建的卷积块的设计。我们提出了一个名为CLC块的设计的例子，这个结构与以前的模型不同，参数较少，计算成本较低。在CLC块的基础上，构造了一个新的卷积神经网络clcNet。 Imagenet-1K数据集上的实验表明，与现有网络相比，clcNet的计算效率更高，参数更少。

##### URL
[http://arxiv.org/abs/1712.06145](http://arxiv.org/abs/1712.06145)

##### PDF
[http://arxiv.org/pdf/1712.06145](http://arxiv.org/pdf/1712.06145)

