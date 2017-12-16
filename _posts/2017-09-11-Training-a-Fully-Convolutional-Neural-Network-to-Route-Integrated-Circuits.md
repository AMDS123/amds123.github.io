---
layout: post
title: "Training a Fully Convolutional Neural Network to Route Integrated Circuits"
date: 2017-09-11 18:37:04
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Sambhav R. Jain, Kye Okabe
mathjax: true
---

* content
{:toc}

##### Abstract
We present a deep, fully convolutional neural network that learns to route a circuit layout net with appropriate choice of metal tracks and wire class combinations. Inputs to the network are the encoded layouts containing spatial location of pins to be routed. After 15 fully convolutional stages followed by a score comparator, the network outputs 8 layout layers (corresponding to 4 route layers, 3 via layers and an identity-mapped pin layer) which are then decoded to obtain the routed layouts. We formulate this as a binary segmentation problem on a per-pixel per-layer basis, where the network is trained to correctly classify pixels in each layout layer to be 'on' or 'off'. To demonstrate learnability of layout design rules, we train the network on a dataset of 50,000 train and 10,000 validation samples that we generate based on certain pre-defined layout constraints. Precision, recall and $F_1$ score metrics are used to track the training progress. Our network achieves $F_1\approx97\%$ on the train set and $F_1\approx92\%$ on the validation set. We use PyTorch for implementing our model. Code is made publicly available at this https URL .

##### Abstract (translated by Google)
我们提出了一个深度的完全卷积神经网络，学习如何通过适当选择金属轨道和导线类组合来路由电路布局网络。对网络的输入是包含要被路由的引脚的空间位置的编码布局。经过15个完全卷积级，然后是分数比较器，网络输出8个布局层（对应于4个路由层，3个通过层和身份映射的引脚层），然后解码以获得路由布局。我们把这个作为一个二进制分割问题，在每个像素的基础上进行分解，在这个网络中，训练网络将每个布局图层中的像素正确地分类为“开”或“关”。为了演示布局设计规则的可学习性，我们根据特定的预定义布局约束条件，在网络上训练了5万个训练数据集和10,000个验证样本。精确度，召回率和$ F_1 $分数指标用于跟踪培训进度。我们的网络在火车上达到$ F_1 \ approx97 \％$，验证集达到$ F_1 \ approx92 \％$。我们使用PyTorch来实现我们的模型。代码在这个https URL上公开。

##### URL
[https://arxiv.org/abs/1706.08948](https://arxiv.org/abs/1706.08948)

##### PDF
[https://arxiv.org/pdf/1706.08948](https://arxiv.org/pdf/1706.08948)

