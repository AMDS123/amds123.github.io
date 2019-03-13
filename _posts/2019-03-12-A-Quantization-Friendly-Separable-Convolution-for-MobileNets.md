---
layout: post
title: "A Quantization-Friendly Separable Convolution for MobileNets"
date: 2019-03-12 17:58:19
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


##### URL
[http://arxiv.org/abs/1803.08607](http://arxiv.org/abs/1803.08607)

##### PDF
[http://arxiv.org/pdf/1803.08607](http://arxiv.org/pdf/1803.08607)

