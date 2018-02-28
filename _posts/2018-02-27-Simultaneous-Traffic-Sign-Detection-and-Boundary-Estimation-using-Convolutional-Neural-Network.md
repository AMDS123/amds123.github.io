---
layout: post
title: "Simultaneous Traffic Sign Detection and Boundary Estimation using Convolutional Neural Network"
date: 2018-02-27 16:51:04
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Optimization Prediction Detection
author: Hee Seok Lee, Kang Kim
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel traffic sign detection system that simultaneously estimates the location and precise boundary of traffic signs using convolutional neural network (CNN). Estimating the precise boundary of traffic signs is important in navigation systems for intelligent vehicles where traffic signs can be used as 3D landmarks for road environment. Previous traffic sign detection systems, including recent methods based on CNN, only provide bounding boxes of traffic signs as output, and thus requires additional processes such as contour estimation or image segmentation to obtain the precise sign boundary. In this work, the boundary estimation of traffic signs is formulated as a 2D pose and shape class prediction problem, and this is effectively solved by a single CNN. With the predicted 2D pose and the shape class of a target traffic sign in an input image, we estimate the actual boundary of the target sign by projecting the boundary of a corresponding template sign image into the input image plane. By formulating the boundary estimation problem as a CNN-based pose and shape prediction task, our method is end-to-end trainable, and more robust to occlusion and small targets than other boundary estimation methods that rely on contour estimation or image segmentation. The proposed method with architectural optimization provides an accurate traffic sign boundary estimation which is also efficient in compute, showing a detection frame rate higher than 7 frames per second on low-power mobile platforms.

##### Abstract (translated by Google)
我们提出了一种新型交通标志检测系统，它使用卷积神经网络（CNN）同时估算交通标志的位置和精确边界。在交通标志可以用作道路环境的三维地标的智能交通工具导航系统中，估算交通标志的精确边界非常重要。先前的交通标志检测系统（包括基于CNN的最新方法）仅提供交通标志的边界框作为输出，并且因此需要诸如轮廓估计或图像分割的附加处理来获得精确的符号边界。在这项工作中，交通标志的边界估计被制定为2D姿态和形状类别预测问题，并且这通过单个CNN有效地解决。通过预测的二维姿态和目标交通标志在输入图像中的形状类别，我们通过将相应的模板符号图像的边界投影到输入图像平面中来估计目标符号的实际边界。通过将边界估计问题表述为基于CNN的姿态和形状预测任务，我们的方法是端对端可训练的，并且比依赖于轮廓估计或图像分割的其他边界估计方法对于遮挡和小目标更稳健。所提出的具有架构优化的方法提供了准确的交通标志边界估计，其在计算上也是有效的，在低功率移动平台上显示高于每秒7帧的检测帧速率。

##### URL
[https://arxiv.org/abs/1802.10019](https://arxiv.org/abs/1802.10019)

##### PDF
[https://arxiv.org/pdf/1802.10019](https://arxiv.org/pdf/1802.10019)

