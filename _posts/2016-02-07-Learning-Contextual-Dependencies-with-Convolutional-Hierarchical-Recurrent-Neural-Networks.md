---
layout: post
title: "Learning Contextual Dependencies with Convolutional Hierarchical Recurrent Neural Networks"
date: 2016-02-07 09:31:36
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN Image_Classification RNN Classification
author: Zhen Zuo, Bing Shuai, Gang Wang, Xiao Liu, Xingxing Wang, Bing Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Existing deep convolutional neural networks (CNNs) have shown their great success on image classification. CNNs mainly consist of convolutional and pooling layers, both of which are performed on local image areas without considering the dependencies among different image regions. However, such dependencies are very important for generating explicit image representation. In contrast, recurrent neural networks (RNNs) are well known for their ability of encoding contextual information among sequential data, and they only require a limited number of network parameters. General RNNs can hardly be directly applied on non-sequential data. Thus, we proposed the hierarchical RNNs (HRNNs). In HRNNs, each RNN layer focuses on modeling spatial dependencies among image regions from the same scale but different locations. While the cross RNN scale connections target on modeling scale dependencies among regions from the same location but different scales. Specifically, we propose two recurrent neural network models: 1) hierarchical simple recurrent network (HSRN), which is fast and has low computational cost; and 2) hierarchical long-short term memory recurrent network (HLSTM), which performs better than HSRN with the price of more computational cost. In this manuscript, we integrate CNNs with HRNNs, and develop end-to-end convolutional hierarchical recurrent neural networks (C-HRNNs). C-HRNNs not only make use of the representation power of CNNs, but also efficiently encodes spatial and scale dependencies among different image regions. On four of the most challenging object/scene image classification benchmarks, our C-HRNNs achieve state-of-the-art results on Places 205, SUN 397, MIT indoor, and competitive results on ILSVRC 2012.

##### Abstract (translated by Google)
现有的深度卷积神经网络（CNNs）在图像分类上取得了巨大的成功。 CNN主要由卷积层和汇聚层组成，二者都是在局部图像区域进行的，而不考虑不同图像区域之间的依赖关系。但是，这种依赖关系对于生成明确的图像表示非常重要。相比之下，递归神经网络（RNN）由于其在顺序数据之间编码上下文信息的能力而众所周知，并且它们仅需要有限数量的网络参数。一般的RNN很难直接应用于非时序数据。因此，我们提出了分层RNN（HRNN）。在HRNN中，每个RNN层侧重于对来自相同比例但不同位置的图像区域之间的空间相关性进行建模。尽管交叉RNN尺度连接针对来自相同位置但不同尺度的区域之间的建模尺度依赖性。具体而言，我们提出了两种递归神经网络模型：1）分层简单递归网络（HSRN），其速度快，计算成本低; 2）分层长短期记忆递归网络（HLSTM），其性能优于HSRN，且计算成本较高。在这篇论文中，我们将CNN与HRNN集成在一起，并开发了端到端的卷积分层递归神经网络（C-HRNN）。 C-HRNN不仅利用了CNN的表示能力，而且有效地编码了不同图像区域之间的空间和尺度依赖关系。在四个最具挑战性的对象/场景图像分类基准测试中，我们的C-HRNN在地方205，SUN 397，麻省理工学院室内获得了最先进的成果，并在ILSVRC 2012上获得了有竞争力的结果。

##### URL
[https://arxiv.org/abs/1509.03877](https://arxiv.org/abs/1509.03877)

##### PDF
[https://arxiv.org/pdf/1509.03877](https://arxiv.org/pdf/1509.03877)

