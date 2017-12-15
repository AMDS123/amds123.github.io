---
layout: post
title: "Full Resolution Image Compression with Recurrent Neural Networks"
date: 2017-07-07 16:26:16
categories: arXiv_CV
tags: arXiv_CV RNN
author: George Toderici, Damien Vincent, Nick Johnston, Sung Jin Hwang, David Minnen, Joel Shor, Michele Covell
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a set of full-resolution lossy image compression methods based on neural networks. Each of the architectures we describe can provide variable compression rates during deployment without requiring retraining of the network: each network need only be trained once. All of our architectures consist of a recurrent neural network (RNN)-based encoder and decoder, a binarizer, and a neural network for entropy coding. We compare RNN types (LSTM, associative LSTM) and introduce a new hybrid of GRU and ResNet. We also study "one-shot" versus additive reconstruction architectures and introduce a new scaled-additive framework. We compare to previous work, showing improvements of 4.3%-8.8% AUC (area under the rate-distortion curve), depending on the perceptual metric used. As far as we know, this is the first neural network architecture that is able to outperform JPEG at image compression across most bitrates on the rate-distortion curve on the Kodak dataset images, with and without the aid of entropy coding.

##### Abstract (translated by Google)
本文提出了一套基于神经网络的全分辨率有损图像压缩方法。我们描述的每种体系结构可以在部署期间提供可变的压缩率，而不需要对网络进行再培训：每个网络只需要训练一次。我们所有的体系结构包括基于递归神经网络（RNN）的编码器和解码器，二进制器和用于熵编码的神经网络。我们比较RNN类型（LSTM，联想LSTM）和引入GRU和ResNet的新混合。我们还研究“一次性”与添加剂重建架构，并引入一个新的缩放添加剂框架。我们比较以前的工作，根据所使用的感知度量，显示出4.3％-8.8％AUC（比率 - 畸变曲线下的面积）的改善。就我们所知，这是第一个能够在JPEG和Kodak数据集图像上的比率 - 失真曲线上的大部分比特率上进行图像压缩的神经网络体系结构，无论是否使用熵编码。

##### URL
[https://arxiv.org/abs/1608.05148](https://arxiv.org/abs/1608.05148)

##### PDF
[https://arxiv.org/pdf/1608.05148](https://arxiv.org/pdf/1608.05148)

