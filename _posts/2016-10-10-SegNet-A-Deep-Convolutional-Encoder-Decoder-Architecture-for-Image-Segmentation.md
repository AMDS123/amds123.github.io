---
layout: post
title: "SegNet: A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation"
date: 2016-10-10 21:11:59
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation CNN Inference Classification
author: Vijay Badrinarayanan, Alex Kendall, Roberto Cipolla
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel and practical deep fully convolutional neural network architecture for semantic pixel-wise segmentation termed SegNet. This core trainable segmentation engine consists of an encoder network, a corresponding decoder network followed by a pixel-wise classification layer. The architecture of the encoder network is topologically identical to the 13 convolutional layers in the VGG16 network. The role of the decoder network is to map the low resolution encoder feature maps to full input resolution feature maps for pixel-wise classification. The novelty of SegNet lies is in the manner in which the decoder upsamples its lower resolution input feature map(s). Specifically, the decoder uses pooling indices computed in the max-pooling step of the corresponding encoder to perform non-linear upsampling. This eliminates the need for learning to upsample. The upsampled maps are sparse and are then convolved with trainable filters to produce dense feature maps. We compare our proposed architecture with the widely adopted FCN and also with the well known DeepLab-LargeFOV, DeconvNet architectures. This comparison reveals the memory versus accuracy trade-off involved in achieving good segmentation performance. SegNet was primarily motivated by scene understanding applications. Hence, it is designed to be efficient both in terms of memory and computational time during inference. It is also significantly smaller in the number of trainable parameters than other competing architectures. We also performed a controlled benchmark of SegNet and other architectures on both road scenes and SUN RGB-D indoor scene segmentation tasks. We show that SegNet provides good performance with competitive inference time and more efficient inference memory-wise as compared to other architectures. We also provide a Caffe implementation of SegNet and a web demo at this http URL

##### Abstract (translated by Google)
我们提出了一种新的，实用的深度全卷积神经网络体系结构，用于SegNet语义像素分割。该核心可训练分割引擎由编码器网络，相应的解码器网络以及随后的逐像素分类层组成。编码器网络的架构在拓扑结构上与VGG16网络中的13个卷积层相同。解码器网络的作用是将低分辨率编码器特征映射映射到用于像素级分类的全输入分辨率特征映射。 SegNet的新颖之处在于解码器上采样其较低分辨率输入特征图的方式。具体地，解码器使用相应编码器的最大池步骤中计算的汇聚指数来执行非线性上采样。这消除了学习上采样的需要。上采样的地图是稀疏的，然后与可训练的滤波器进行卷积以产生密集的特征地图。我们将我们提出的架构与广泛采用的FCN以及众所周知的DeepLab-LargeFOV，DeconvNet架构进行比较。这个比较揭示了实现良好分割性能所涉及的内存与精度之间的平衡。 SegNet的主要动机是场景理解应用程序。因此，它被设计成在推理期间在存储器和计算时间方面都是有效的。与其他竞争架构相比，可训练参数的数量也明显减少。我们还在道路场景和SUN RGB-D室内场景分割任务上执行了SegNet和其他架构的控制基准。我们展示SegNet与其他体系结构相比，提供了具有竞争性推断时间的良好性能和更高效的内存推理。我们还在这个http URL上提供了SegNet的Caffe实现和一个Web演示

##### URL
[https://arxiv.org/abs/1511.00561](https://arxiv.org/abs/1511.00561)

##### PDF
[https://arxiv.org/pdf/1511.00561](https://arxiv.org/pdf/1511.00561)

