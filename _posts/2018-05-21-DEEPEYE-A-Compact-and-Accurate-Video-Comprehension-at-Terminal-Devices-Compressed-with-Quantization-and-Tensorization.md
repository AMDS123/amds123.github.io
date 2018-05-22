---
layout: post
title: "DEEPEYE: A Compact and Accurate Video Comprehension at Terminal Devices Compressed with Quantization and Tensorization"
date: 2018-05-21 08:08:07
categories: arXiv_AI
tags: arXiv_AI Object_Detection Action_Recognition Optimization RNN Classification Detection Recognition
author: Yuan Cheng, Guangya Li, Hai-Bao Chen, Sheldon X.-D. Tan, Hao Yu
mathjax: true
---

* content
{:toc}

##### Abstract
As it requires a huge number of parameters when exposed to high dimensional inputs in video detection and classification, there is a grand challenge to develop a compact yet accurate video comprehension at terminal devices. Current works focus on optimizations of video detection and classification in a separated fashion. In this paper, we introduce a video comprehension (object detection and action recognition) system for terminal devices, namely DEEPEYE. Based on You Only Look Once (YOLO), we have developed an 8-bit quantization method when training YOLO; and also developed a tensorized-compression method of Recurrent Neural Network (RNN) composed of features extracted from YOLO. The developed quantization and tensorization can significantly compress the original network model yet with maintained accuracy. Using the challenging video datasets: MOMENTS and UCF11 as benchmarks, the results show that the proposed DEEPEYE achieves 3.994x model compression rate with only 0.47% mAP decreased; and 15,047x parameter reduction and 2.87x speed-up with 16.58% accuracy improvement.

##### Abstract (translated by Google)
由于在视频检测和分类中暴露于高维度输入时需要大量参数，因此在终端设备上开发紧凑且精确的视频理解存在巨大挑战。当前的着作集中于视频检测和分类方面的优化。在本文中，我们介绍了终端设备的视频理解（对象检测和动作识别）系统，即DEEPEYE。基于你只看一次（YOLO），我们开发了一个8位量化方法来训练YOLO;并开发了由YOLO提取的特征构成的递归神经网络（RNN）的张量压缩方法。开发出的量化和张量化能够在保持精确度的同时大幅度压缩原始网络模型。使用具有挑战性的视频数据集：MOMENTS和UCF11作为基准，结果表明，提出的DEEPEYE达到了3.994倍的模型压缩率，仅有0.47％的mAP降低;和15,047x参数缩减和2.87倍加速，精度提高了16.58％。

##### URL
[https://arxiv.org/abs/1805.07935](https://arxiv.org/abs/1805.07935)

##### PDF
[https://arxiv.org/pdf/1805.07935](https://arxiv.org/pdf/1805.07935)

