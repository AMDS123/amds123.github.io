---
layout: post
title: "Video Deblurring via Semantic Segmentation and Pixel-Wise Non-Linear Kernel"
date: 2017-08-11 03:15:48
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Relation
author: Wenqi Ren, Jinshan Pan, Xiaochun Cao, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Video deblurring is a challenging problem as the blur is complex and usually caused by the combination of camera shakes, object motions, and depth variations. Optical flow can be used for kernel estimation since it predicts motion trajectories. However, the estimates are often inaccurate in complex scenes at object boundaries, which are crucial in kernel estimation. In this paper, we exploit semantic segmentation in each blurry frame to understand the scene contents and use different motion models for image regions to guide optical flow estimation. While existing pixel-wise blur models assume that the blur kernel is the same as optical flow during the exposure time, this assumption does not hold when the motion blur trajectory at a pixel is different from the estimated linear optical flow. We analyze the relationship between motion blur trajectory and optical flow, and present a novel pixel-wise non-linear kernel model to account for motion blur. The proposed blur model is based on the non-linear optical flow, which describes complex motion blur more effectively. Extensive experiments on challenging blurry videos demonstrate the proposed algorithm performs favorably against the state-of-the-art methods.

##### Abstract (translated by Google)
视频去模糊是一个具有挑战性的问题，因为模糊是复杂的，并且通常由相机抖动，对象运动和深度变化的组合引起。光流可以用于核估计，因为它可以预测运动轨迹。然而，在对象边界的复杂场景中，估计往往是不准确的，这在核心估计中是至关重要的。在本文中，我们利用每个模糊帧中的语义分割来理解场景内容，并使用不同的运动模型来指导图像区域的光流估计。虽然现有的逐像素模糊模型假定在曝光时间期间模糊内核与光流相同，但是当像素处的运动模糊轨迹与估计的线性光流不同时，该假设不成立。我们分析了运动模糊轨迹和光流之间的关系，提出了一种新的像素非线性核模型来解决运动模糊问题。所提出的模糊模型是基于非线性光流，其更加有效地描述了复杂的运动模糊。针对具有挑战性的模糊视频的大量实验证明了所提出的算法对于最先进的方法有良好的效果。

##### URL
[https://arxiv.org/abs/1708.03423](https://arxiv.org/abs/1708.03423)

##### PDF
[https://arxiv.org/pdf/1708.03423](https://arxiv.org/pdf/1708.03423)

