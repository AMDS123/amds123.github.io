---
layout: post
title: "Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation"
date: 2018-08-22 20:41:10
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Liang-Chieh Chen, Yukun Zhu, George Papandreou, Florian Schroff, Hartwig Adam
mathjax: true
---

* content
{:toc}

##### Abstract
Spatial pyramid pooling module or encode-decoder structure are used in deep neural networks for semantic segmentation task. The former networks are able to encode multi-scale contextual information by probing the incoming features with filters or pooling operations at multiple rates and multiple effective fields-of-view, while the latter networks can capture sharper object boundaries by gradually recovering the spatial information. In this work, we propose to combine the advantages from both methods. Specifically, our proposed model, DeepLabv3+, extends DeepLabv3 by adding a simple yet effective decoder module to refine the segmentation results especially along object boundaries. We further explore the Xception model and apply the depthwise separable convolution to both Atrous Spatial Pyramid Pooling and decoder modules, resulting in a faster and stronger encoder-decoder network. We demonstrate the effectiveness of the proposed model on PASCAL VOC 2012 and Cityscapes datasets, achieving the test set performance of 89.0\% and 82.1\% without any post-processing. Our paper is accompanied with a publicly available reference implementation of the proposed models in Tensorflow at \url{https://github.com/tensorflow/models/tree/master/research/deeplab}.

##### Abstract (translated by Google)
空间金字塔池模块或编码 - 解码器结构用于深度神经网络中用于语义分割任务。前一种网络能够通过利用多个速率和多个有效视场的过滤器或池化操作探测传入特征来编码多尺度上下文信息，而后一种网络可以通过逐渐恢复空间信息来捕获更清晰的对象边界。在这项工作中，我们建议结合两种方法的优点。具体来说，我们提出的模型DeepLabv3 +通过添加一个简单而有效的解码器模块来扩展DeepLabv3，以优化分割结果，尤其是沿着对象边界。我们进一步探索Xception模型并将深度可分离卷积应用于Atrous Spatial Pyramid Pooling和解码器模块，从而产生更快更强的编码器 - 解码器网络。我们证明了所提出的模型在PASCAL VOC 2012和Cityscapes数据集上的有效性，在没有任何后处理的情况下实现了89.0％和82.1％的测试集性能。我们的论文附有Tensorflow中提议模型的公开参考实现，网址为\ url {https://github.com/tensorflow/models/tree/master/research/deeplab}。

##### URL
[http://arxiv.org/abs/1802.02611](http://arxiv.org/abs/1802.02611)

##### PDF
[http://arxiv.org/pdf/1802.02611](http://arxiv.org/pdf/1802.02611)

