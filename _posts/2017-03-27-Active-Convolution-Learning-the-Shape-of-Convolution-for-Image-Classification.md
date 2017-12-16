---
layout: post
title: "Active Convolution: Learning the Shape of Convolution for Image Classification"
date: 2017-03-27 13:44:26
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Deep_Learning
author: Yunho Jeon, Junmo Kim
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, deep learning has achieved great success in many computer vision applications. Convolutional neural networks (CNNs) have lately emerged as a major approach to image classification. Most research on CNNs thus far has focused on developing architectures such as the Inception and residual networks. The convolution layer is the core of the CNN, but few studies have addressed the convolution unit itself. In this paper, we introduce a convolution unit called the active convolution unit (ACU). A new convolution has no fixed shape, because of which we can define any form of convolution. Its shape can be learned through backpropagation during training. Our proposed unit has a few advantages. First, the ACU is a generalization of convolution; it can define not only all conventional convolutions, but also convolutions with fractional pixel coordinates. We can freely change the shape of the convolution, which provides greater freedom to form CNN structures. Second, the shape of the convolution is learned while training and there is no need to tune it by hand. Third, the ACU can learn better than a conventional unit, where we obtained the improvement simply by changing the conventional convolution to an ACU. We tested our proposed method on plain and residual networks, and the results showed significant improvement using our method on various datasets and architectures in comparison with the baseline.

##### Abstract (translated by Google)
近年来，深度学习在许多计算机视觉应用中取得了巨大的成功。卷积神经网络（CNN）最近已经成为图像分类的主要方法。迄今为止，有关CNN的大多数研究集中在开发初始和剩余网络等体系结构上。卷积层是CNN的核心，但很少有研究涉及卷积单元本身。在本文中，我们介绍一个称为主动卷积单元（ACU）的卷积单元。一个新的卷积没有固定的形状，因此我们可以定义任何形式的卷积。训练期间通过反向传播可以学习其形状。我们建议的单位有一些优点。首先，ACU是卷积的推广;它不仅可以定义所有常规的卷积，而且可以定义具有分数像素坐标的卷积。我们可以自由地改变卷积的形状，这为形成CNN结构提供了更大的自由度。其次，卷积的形状是在训练时学习的，不需要手工调整。第三，ACU可以比传统单元更好地学习，我们通过简单地将常规卷积改变为ACU来获得改进。我们在纯网络和残差网络上测试了我们提出的方法，结果显示，与基线相比，使用我们的方法在各种数据集和体系结构上显着改善。

##### URL
[https://arxiv.org/abs/1703.09076](https://arxiv.org/abs/1703.09076)

##### PDF
[https://arxiv.org/pdf/1703.09076](https://arxiv.org/pdf/1703.09076)

