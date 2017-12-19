---
layout: post
title: "Learning a Virtual Codec Based on Deep Convolutional Neural Network to Compress Image"
date: 2017-12-16 14:55:13
categories: arXiv_CV
tags: arXiv_CV CNN
author: Lijun Zhao, Huihui Bai, Anhong Wang, Yao Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep neural network has been proved to efficiently eliminate the coding artifacts caused by the coarse quantization of traditional codec, it's difficult to train any neural network in front of the encoder for gradient's back-propagation. In this paper, we propose an end-to-end image compression framework based on neural network framework to resolve the problem of non-differentiability of the quantization function in the standard codec. First, the feature description neural network is used to get a valid description in the low-dimension space with respect to the ground-truth image so that the amount of image data is greatly reduced for storage or transmission. After image's valid description, standard image codec such as JPEG is leveraged to further compress image, which leads to image's great distortion and compression artifacts, especially blocking artifacts, detail missing, blurring, and ringing artifacts. Then, we use a post-processing neural network to remove these artifacts. Due to the challenge of directly learning a codec based convolutional neural network, we propose to learn a virtual codec neural network to approximate the projection from valid description image to the post-processed compressed image, so that the gradient could be efficiently back-propagated from the post-processing neural networks to the feature description neural network during training. Meanwhile, an advanced learning algorithm is proposed to train our deep neural networks for compression. Obviously, the priority of the proposed method is compatible with standard existing codecs and our learning strategy can be easily extended into these codecs based on neural network. Experimental results have demonstrated the advances of the proposed method as compared to several state-of-the-art approaches, especially at very low bit-rate.

##### Abstract (translated by Google)
虽然深度神经网络已经被证明能够有效地消除由于传统编解码器的粗量化而引起的编码伪像，但是在编码器之前训练任何神经网络以用于梯度反向传播是困难的。在本文中，我们提出了一种基于神经网络框架的端到端图像压缩框架，以解决标准编解码器中量化函数的不可分性问题。首先利用特征描述神经网络在低维空间中对地面真实图像进行有效描述，从而大大减少了图像数据的存储量或传输量。图像的有效描述后，利用JPEG等标准图像编解码器进一步压缩图像，导致图像的失真和压缩失真较大，特别是块效应，细节丢失，模糊和振铃伪像。然后，我们使用后处理神经网络去除这些文物。由于直接学习基于编解码器的卷积神经网络的挑战，我们建议学习一个虚拟编解码器神经网络来逼近从有效描述图像到后处理压缩图像的投影，使得梯度可以被有效地反向传播对训练过程中的特征描述神经网络进行后处理神经网络。同时提出了一种高级学习算法来训练我们的深度神经网络进行压缩。显然，所提出的方法的优先级与标准的现有编解码器兼容，并且我们的学习策略可以容易地扩展到基于神经网络的这些编解码器中。实验结果证明了与几种最先进的方法相比，所提出的方法的进步，特别是在非常低的比特率下。

##### URL
[http://arxiv.org/abs/1712.05969](http://arxiv.org/abs/1712.05969)

##### PDF
[http://arxiv.org/pdf/1712.05969](http://arxiv.org/pdf/1712.05969)

