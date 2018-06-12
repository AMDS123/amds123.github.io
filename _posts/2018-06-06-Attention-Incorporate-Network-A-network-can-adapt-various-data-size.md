---
layout: post
title: "Attention Incorporate Network: A network can adapt various data size"
date: 2018-06-06 11:09:35
categories: arXiv_CV
tags: arXiv_CV Attention RNN
author: Liangbo He, Hao Sun
mathjax: true
---

* content
{:toc}

##### Abstract
In traditional neural networks for image processing, the inputs of the neural networks should be the same size such as 224*224*3. But how can we train the neural net model with different input size? A common way to do is image deformation which accompany a problem of information loss (e.g. image crop or wrap). Sequence model(RNN, LSTM, etc.) can accept different size of input like text and audio. But one disadvantage for sequence model is that the previous information will become more fragmentary during the transfer in time step, it will make the network hard to train especially for long sequential data. In this paper we propose a new network structure called Attention Incorporate Network(AIN). It solve the problem of different size of inputs including: images, text, audio, and extract the key features of the inputs by attention mechanism, pay different attention depends on the importance of the features not rely on the data size. Experimentally, AIN achieve a higher accuracy, better convergence comparing to the same size of other network structure

##### Abstract (translated by Google)
在用于图像处理的传统神经网络中，神经网络的输入应该是相同的大小，例如224 * 224 * 3。但是，我们如何训练不同输入大小的神经网络模型呢？一种常见的方法是伴随信息丢失问题（例如图像裁剪或包装）的图像变形。序列模型（RNN，LSTM等）可以接受不同大小的输入，如文本和音频。但序列模型的一个缺点是，在时间传递的过程中，先前的信息将变得更加零碎，这将使网络很难专门针对长序列数据进行训练。在本文中，我们提出了一种称为注意整合网络（AIN）的新网络结构。它解决了输入大小不同的问题，包括：图像，文本，音频，并通过注意机制提取输入的关键特征，不同的注意力取决于不依赖于数据大小的特征的重要性。实验中，与其他网络结构的相同尺寸相比，AIN实现更高的精度，更好的收敛性

##### URL
[http://arxiv.org/abs/1806.03961](http://arxiv.org/abs/1806.03961)

##### PDF
[http://arxiv.org/pdf/1806.03961](http://arxiv.org/pdf/1806.03961)

