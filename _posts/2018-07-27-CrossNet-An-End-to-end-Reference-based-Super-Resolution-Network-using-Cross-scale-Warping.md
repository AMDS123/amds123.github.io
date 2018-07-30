---
layout: post
title: "CrossNet: An End-to-end Reference-based Super Resolution Network using Cross-scale Warping"
date: 2018-07-27 12:15:40
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Optimization
author: Haitian Zheng, Mengqi Ji, Haoqian Wang, Yebin Liu, Lu Fang
mathjax: true
---

* content
{:toc}

##### Abstract
The Reference-based Super-resolution (RefSR) super-resolves a low-resolution (LR) image given an external high-resolution (HR) reference image, where the reference image and LR image share similar viewpoint but with significant resolution gap x8. Existing RefSR methods work in a cascaded way such as patch matching followed by synthesis pipeline with two independently defined objective functions, leading to the inter-patch misalignment, grid effect and inefficient optimization. To resolve these issues, we present CrossNet, an end-to-end and fully-convolutional deep neural network using cross-scale warping. Our network contains image encoders, cross-scale warping layers, and fusion decoder: the encoder serves to extract multi-scale features from both the LR and the reference images; the cross-scale warping layers spatially aligns the reference feature map with the LR feature map; the decoder finally aggregates feature maps from both domains to synthesize the HR output. Using cross-scale warping, our network is able to perform spatial alignment at pixel-level in an end-to-end fashion, which improves the existing schemes both in precision (around 2dB-4dB) and efficiency (more than 100 times faster).

##### Abstract (translated by Google)
给定外部高分辨率（HR）参考图像的基于参考的超分辨率（RefSR）超分辨率低分辨率（LR）图像，其中参考图像和LR图像共享相似的视点但具有显着的分辨率间隙x8。现有的RefSR方法以级联的方式工作，例如补丁匹配，然后是具有两个独立定义的目标函数的合成流水线，导致补丁间错位，网格效应和低效优化。为了解决这些问题，我们提出了CrossNet，一种使用跨尺度变形的端到端和全卷积深度神经网络。我们的网络包含图像编码器，交叉规模变形图层和融合解码器：编码器用于从LR和参考图像中提取多尺度特征;交叉比例翘曲层在空间上将参考特征图与LR特征图对齐;解码器最终聚合来自两个域的特征映射以合成HR输出。使用跨尺度变形，我们的网络能够以端到端的方式在像素级执行空间对齐，从而改善现有方案的精度（大约2dB-4dB）和效率（超过100倍） 。

##### URL
[http://arxiv.org/abs/1807.10547](http://arxiv.org/abs/1807.10547)

##### PDF
[http://arxiv.org/pdf/1807.10547](http://arxiv.org/pdf/1807.10547)

