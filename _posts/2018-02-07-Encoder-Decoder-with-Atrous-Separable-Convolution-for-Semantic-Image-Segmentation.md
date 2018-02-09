---
layout: post
title: "Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation"
date: 2018-02-07 19:37:11
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Liang-Chieh Chen, Yukun Zhu, George Papandreou, Florian Schroff, Hartwig Adam
mathjax: true
---

* content
{:toc}

##### Abstract
Spatial pyramid pooling module or encode-decoder structure are used in deep neural networks for semantic segmentation task. The former networks are able to encode multi-scale contextual information by probing the incoming features with filters or pooling operations at multiple rates and multiple effective fields-of-view, while the latter networks can capture sharper object boundaries by gradually recovering the spatial information. In this work, we propose to combine the advantages from both methods. Specifically, our proposed model, DeepLabv3+, extends DeepLabv3 by adding a simple yet effective decoder module to refine the segmentation results especially along object boundaries. We further explore the Xception model and apply the depthwise separable convolution to both Atrous Spatial Pyramid Pooling and decoder modules, resulting in a faster and stronger encoder-decoder network. We demonstrate the effectiveness of the proposed model on the PASCAL VOC 2012 semantic image segmentation dataset and achieve a performance of 89% on the test set without any post-processing. Our paper is accompanied with a publicly available reference implementation of the proposed models in Tensorflow.

##### Abstract (translated by Google)
在深度神经网络中使用空间金字塔池模块或编解码器结构进行语义分割任务。前者网络能够通过以多速率和多个有效视场探测具有滤波器或汇集操作的输入特征来对多尺度上下文信息进行编码，而后者网络能够通过逐渐恢复空间信息来捕获更清晰的对象边界。在这项工作中，我们建议结合两种方法的优点。具体来说，我们提出的模型DeepLabv3 +通过添加一个简单而有效的解码器模块来扩展DeepLabv3，以细化分割结果，特别是沿着对象边界。我们进一步探索Xception模型，并将深度可分卷积应用于Atrous Spatial Pyramid Pooling和解码器模块，从而形成更快更强的编解码器网络。我们证明了该模型在PASCAL VOC 2012语义图像分割数据集上的有效性，并且在没有任何后处理的情况下在测试集上实现了89％的性能。我们的论文伴随着Tensorflow中提出的模型的公开可用参考实现。

##### URL
[http://arxiv.org/abs/1802.02611](http://arxiv.org/abs/1802.02611)

##### PDF
[http://arxiv.org/pdf/1802.02611](http://arxiv.org/pdf/1802.02611)

