---
layout: post
title: "A Quantization-Friendly Separable Convolution for MobileNets"
date: 2018-03-22 23:06:38
categories: arXiv_CV
tags: arXiv_CV Image_Classification Inference Classification Deep_Learning
author: Tao Sheng, Chen Feng, Shaojie Zhuo, Xiaopeng Zhang, Liang Shen, Mickey Aleksic
mathjax: true
---

* content
{:toc}

##### Abstract
As deep learning (DL) is being rapidly pushed to edge computing, researchers invented various ways to make inference computation more efficient on mobile/IoT devices, such as network pruning, parameter compression, and etc. Quantization, as one of the key approaches, can effectively offload GPU, and make it possible to deploy DL on fixed-point pipeline. Unfortunately, not all existing networks design are friendly to quantization. For example, the popular lightweight MobileNetV1, while it successfully reduces parameter size and computation latency with separable convolution, our experiment shows its quantized models have large accuracy gap against its float point models. To resolve this, we analyzed the root cause of quantization loss and proposed a quantization-friendly separable convolution architecture. By evaluating the image classification task on ImageNet2012 dataset, our modified MobileNetV1 model can archive 8-bit inference top-1 accuracy in 68.03%, almost closed the gap to the float pipeline.

##### Abstract (translated by Google)
随着深度学习（DL）被迅速推到边缘计算领域，研究人员发明了各种方法来使移动/ IoT设备上的推理计算更加高效，如网络修剪，参数压缩等。量化作为关键方法之一，可以有效地卸载GPU，并且可以将DL部署在定点流水线上。不幸的是，并不是所有现有的网络设计都对量化友好。例如，流行的轻量级MobileNetV1虽然通过可分离卷积成功减少了参数大小和计算延迟，但我们的实验显示其量化模型与浮点模型相比具有较大的精度差距。为了解决这个问题，我们分析了量化损失的根本原因并提出了一种量化友好的可分离卷积结构。通过评估ImageNet2012数据集上的图像分类任务，我们修改后的MobileNetV1模型可将68.03％的8位推断top-1精度归档，几乎封闭了与浮动管道的差距。

##### URL
[https://arxiv.org/abs/1803.08607](https://arxiv.org/abs/1803.08607)

##### PDF
[https://arxiv.org/pdf/1803.08607](https://arxiv.org/pdf/1803.08607)

