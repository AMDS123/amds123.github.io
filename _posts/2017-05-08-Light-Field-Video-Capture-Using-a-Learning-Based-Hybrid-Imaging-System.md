---
layout: post
title: "Light Field Video Capture Using a Learning-Based Hybrid Imaging System"
date: 2017-05-08 17:56:44
categories: arXiv_CV
tags: arXiv_CV CNN
author: Ting-Chun Wang, Jun-Yan Zhu, Nima Khademi Kalantari, Alexei A. Efros, Ravi Ramamoorthi
mathjax: true
---

* content
{:toc}

##### Abstract
Light field cameras have many advantages over traditional cameras, as they allow the user to change various camera settings after capture. However, capturing light fields requires a huge bandwidth to record the data: a modern light field camera can only take three images per second. This prevents current consumer light field cameras from capturing light field videos. Temporal interpolation at such extreme scale (10x, from 3 fps to 30 fps) is infeasible as too much information will be entirely missing between adjacent frames. Instead, we develop a hybrid imaging system, adding another standard video camera to capture the temporal information. Given a 3 fps light field sequence and a standard 30 fps 2D video, our system can then generate a full light field video at 30 fps. We adopt a learning-based approach, which can be decomposed into two steps: spatio-temporal flow estimation and appearance estimation. The flow estimation propagates the angular information from the light field sequence to the 2D video, so we can warp input images to the target view. The appearance estimation then combines these warped images to output the final pixels. The whole process is trained end-to-end using convolutional neural networks. Experimental results demonstrate that our algorithm outperforms current video interpolation methods, enabling consumer light field videography, and making applications such as refocusing and parallax view generation achievable on videos for the first time.

##### Abstract (translated by Google)
与传统相机相比，光场相机具有许多优点，因为它们允许用户在拍摄之后改变各种相机设置。但是，捕捉光场需要巨大的带宽来记录数据：现代的光场相机每秒只能拍摄三幅图像。这可以防止当前的消费者光场相机捕捉光场视频。在如此极端的尺度上（10x，从3fps到30fps）的时间内插是不可行的，因为太多的信息将在相邻帧之间完全丢失。相反，我们开发了一个混合成像系统，增加了另一个标准的摄像机来捕捉时间信息。给定3 fps的光场序列和标准的30 fps 2D视频，我们的系统可以生成30 fps的全光场视频。我们采用基于学习的方法，可以分解为两个步骤：时空流量估计和外观估计。流量估计将角度信息从光场序列传播到2D视频，因此我们可以将输入图像变形到目标视图。外观估计然后组合这些变形的图像以输出最终的像素。整个过程是使用卷积神经网络进行端到端的训练。实验结果表明，我们的算法优于目前的视频插值方法，使消费者的光场摄像，并使第一次在视频上实现重新聚焦和视差视图生成的应用。

##### URL
[https://arxiv.org/abs/1705.02997](https://arxiv.org/abs/1705.02997)

##### PDF
[https://arxiv.org/pdf/1705.02997](https://arxiv.org/pdf/1705.02997)

