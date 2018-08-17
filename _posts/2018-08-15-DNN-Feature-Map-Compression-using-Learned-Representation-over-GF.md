---
layout: post
title: "DNN Feature Map Compression using Learned Representation over GF"
date: 2018-08-15 21:13:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Classification Detection
author: Denis A. Gudovskiy, Alec Hodgkinson, Luca Rigazio
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a method to compress intermediate feature maps of deep neural networks (DNNs) to decrease memory storage and bandwidth requirements during inference. Unlike previous works, the proposed method is based on converting fixed-point activations into vectors over the smallest GF(2) finite field followed by nonlinear dimensionality reduction (NDR) layers embedded into a DNN. Such an end-to-end learned representation finds more compact feature maps by exploiting quantization redundancies within the fixed-point activations along the channel or spatial dimensions. We apply the proposed network architectures derived from modified SqueezeNet and MobileNetV2 to the tasks of ImageNet classification and PASCAL VOC object detection. Compared to prior approaches, the conducted experiments show a factor of 2 decrease in memory requirements with minor degradation in accuracy while adding only bitwise computations.

##### Abstract (translated by Google)
在本文中，我们介绍了一种压缩深度神经网络（DNN）中间特征映射的方法，以减少推理期间的内存存储和带宽需求。与以前的工作不同，所提出的方法基于将定点激活转换为最小GF（2）有限域上的向量，随后是嵌入到DNN中的非线性降维（NDR）层。这种端到端学习表示通过利用沿着信道或空间维度的定点激活内的量化冗余来找到更紧凑的特征图。我们将从修改后的SqueezeNet和MobileNetV2派生的建议网络架构应用于ImageNet分类和PASCAL VOC对象检测的任务。与现有方法相比，所进行的实验显示存储器要求降低2倍，精度稍微降低，同时仅添加按位计算。

##### URL
[http://arxiv.org/abs/1808.05285](http://arxiv.org/abs/1808.05285)

##### PDF
[http://arxiv.org/pdf/1808.05285](http://arxiv.org/pdf/1808.05285)

