---
layout: post
title: "Efficient Dense Modules of Asymmetric Convolution for Real-Time Semantic Segmentation"
date: 2018-09-17 16:52:46
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference
author: Shao-Yuan Lo, Hsueh-Ming Hang, Sheng-Wei Chan, Jing-Jhih Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time semantic segmentation plays an important role in practical applications such as self-driving and robots. Most research working on semantic segmentation focuses on accuracy with little consideration for efficiency. Several existing studies that emphasize high-speed inference often cannot produce high-accuracy segmentation results. In this paper, we propose a novel convolutional network named Efficient Dense modules with Asymmetric convolution (EDANet), which employs an asymmetric convolution structure incorporating the dilated convolution and the dense connectivity to attain high efficiency at low computational cost, inference time, and model size. Compared to FCN, EDANet is 11 times faster and has 196 times fewer parameters, while it achieves a higher the mean of intersection-over-union (mIoU) score without any additional decoder structure, context module, post-processing scheme, and pretrained model. We evaluate EDANet on Cityscapes and CamVid datasets to evaluate its performance and compare it with the other state-of-art systems. Our network can run on resolution 512x1024 inputs at the speed of 108 and 81 frames per second on a single GTX 1080Ti and Titan X, respectively.

##### Abstract (translated by Google)
实时语义分割在诸如自动驾驶和机器人等实际应用中起着重要作用。大多数从事语义分割的研究都侧重于准确性而很少考虑效率。一些强调高速推理的现有研究往往不能产生高精度的分割结果。在本文中，我们提出了一种新的卷积网络，称为带有非对称卷积的高效密集模块（EDANet），它采用非对称卷积结构，结合了扩张卷积和密集连通性，以低计算成本，推理时间和模型大小获得高效率。 。与FCN相比，EDANet的速度提高了11倍，参数减少了196倍，同时无需任何额外的解码器结构，上下文模块，后处理方案和预训练模型，它实现了更高的交叉结合平均值（mIoU）得分。 。我们评估城市景观和CamVid数据集上的EDANet，以评估其性能，并将其与其他最先进的系统进行比较。我们的网络可以分别在单个GTX 1080Ti和Titan X上以108和81帧/秒的速度运行分辨率512x1024输入。

##### URL
[http://arxiv.org/abs/1809.06323](http://arxiv.org/abs/1809.06323)

##### PDF
[http://arxiv.org/pdf/1809.06323](http://arxiv.org/pdf/1809.06323)

