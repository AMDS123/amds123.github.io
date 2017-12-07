---
layout: post
title: "LCDet: Low-Complexity Fully-Convolutional Neural Networks for Object Detection in Embedded Systems"
date: 2017-05-16 21:05:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Image_Classification Classification Detection Face_Detection
author: Subarna Tripathi, Gokce Dane, Byeongkeun Kang, Vasudev Bhaskaran, Truong Nguyen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional Neural Networks (CNN) are the state-of-the-art performers for object detection task. It is well known that object detection requires more computation and memory than image classification. Thus the consolidation of a CNN-based object detection for an embedded system is more challenging. In this work, we propose LCDet, a fully-convolutional neural network for generic object detection that aims to work in embedded systems. We design and develop an end-to-end TensorFlow(TF)-based model. Additionally, we employ 8-bit quantization on the learned weights. We use face detection as a use case. Our TF-Slim based network can predict different faces of different shapes and sizes in a single forward pass. Our experimental results show that the proposed method achieves comparative accuracy comparing with state-of-the-art CNN-based face detection methods, while reducing the model size by 3x and memory-BW by ~4x comparing with one of the best real-time CNN-based object detector such as YOLO. TF 8-bit quantized model provides additional 4x memory reduction while keeping the accuracy as good as the floating point model. The proposed model thus becomes amenable for embedded implementations.

##### Abstract (translated by Google)
深卷积神经网络（CNN）是目标检测任务的最先进的执行者。众所周知，与图像分类相比，对象检测需要更多的计算和内存。因此，为嵌入式系统整合基于CNN的对象检测更具挑战性。在这项工作中，我们提出了LCDet，一个通用对象检测的全卷积神经网络，旨在在嵌入式系统中工作。我们设计和开发了一个端到端的基于TensorFlow（TF）的模型。另外，我们对学习权重采用8位量化。我们使用人脸检测作为用例。我们的基于TF-Slim的网络可以预测不同形状和尺寸的不同面孔。我们的实验结果表明，与最先进的基于CNN的人脸检测方法相比，所提出的方法达到了比较的准确性，同时与最佳实时之一相比，将模型大小减少了3倍，存储器带宽减少了4倍基于CNN的对象检测器，如YOLO。 TF 8位量化模型提供额外的4倍内存减少，同时保持与浮点模型一样的精确度。所提出的模型因此变得适用于嵌入式实现。

##### URL
[https://arxiv.org/abs/1705.05922](https://arxiv.org/abs/1705.05922)

##### PDF
[https://arxiv.org/pdf/1705.05922](https://arxiv.org/pdf/1705.05922)

