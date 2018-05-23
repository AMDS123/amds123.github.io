---
layout: post
title: "Highly Efficient 8-bit Low Precision Inference of Convolutional Neural Networks with IntelCaffe"
date: 2018-05-04 07:58:33
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Inference Deep_Learning
author: Jiong Gong, Haihao Shen, Guoming Zhang, Xiaoli Liu, Shane Li, Ge Jin, Niharika Maheshwari, Evarist Fomenko, Eden Segal
mathjax: true
---

* content
{:toc}

##### Abstract
High throughput and low latency inference of deep neural networks are critical for the deployment of deep learning applications. This paper presents the efficient inference techniques of IntelCaffe, the first Intel optimized deep learning framework that supports efficient 8-bit low precision inference and model optimization techniques of convolutional neural networks on Intel Xeon Scalable Processors. The 8-bit optimized model is automatically generated with a calibration process from FP32 model without the need of fine-tuning or retraining. We show that the inference throughput and latency with ResNet-50, Inception-v3 and SSD are improved by 1.38X-2.9X and 1.35X-3X respectively with neglectable accuracy loss from IntelCaffe FP32 baseline and by 56X-75X and 26X-37X from BVLC Caffe. All these techniques have been open-sourced on IntelCaffe GitHub1, and the artifact is provided to reproduce the result on Amazon AWS Cloud.

##### Abstract (translated by Google)
深度神经网络的高吞吐量和低延迟推断对于深度学习应用的部署至关重要。本文介绍IntelCaffe的高效推理技术，这是英特尔第一个优化的深度学习框架，支持英特尔至强可升级处理器上高效的8位低精度推理和卷积神经网络的模型优化技术。 8位优化模型可自动生成FP32模型的校准过程，无需进行微调或重新训练。我们发现，ResNet-50，Inception-v3和SSD的推理吞吐量和延迟分别提高了1.38X-2.9X和1.35X-3X，IntelCaffe FP32基准线的准确度损失可以忽略不计，而56X-75X和26X-37X BVLC Caffe。所有这些技术都是在IntelCaffe GitHub1上开源的，并且提供了工件以在Amazon AWS Cloud上重现结果。

##### URL
[https://arxiv.org/abs/1805.08691](https://arxiv.org/abs/1805.08691)

##### PDF
[https://arxiv.org/pdf/1805.08691](https://arxiv.org/pdf/1805.08691)

