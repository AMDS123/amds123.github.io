---
layout: post
title: "Peeking Behind Objects: Layered Depth Prediction from a Single Image"
date: 2018-07-23 18:23:53
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Prediction
author: Helisa Dhamo, Keisuke Tateno, Iro Laina, Nassir Navab, Federico Tombari
mathjax: true
---

* content
{:toc}

##### Abstract
While conventional depth estimation can infer the geometry of a scene from a single RGB image, it fails to estimate scene regions that are occluded by foreground objects. This limits the use of depth prediction in augmented and virtual reality applications, that aim at scene exploration by synthesizing the scene from a different vantage point, or at diminished reality. To address this issue, we shift the focus from conventional depth map prediction to the regression of a specific data representation called Layered Depth Image (LDI), which contains information about the occluded regions in the reference frame and can fill in occlusion gaps in case of small view changes. We propose a novel approach based on Convolutional Neural Networks (CNNs) to jointly predict depth maps and foreground separation masks used to condition Generative Adversarial Networks (GANs) for hallucinating plausible color and depths in the initially occluded areas. We demonstrate the effectiveness of our approach for novel scene view synthesis from a single image.

##### Abstract (translated by Google)
虽然传统的深度估计可以从单个RGB图像推断出场景的几何形状，但是它无法估计被前景对象遮挡的场景区域。这限制了在增强和虚拟现实应用中的深度预测的使用，其旨在通过从不同的有利位置或在减少的现实中合成场景来进行场景探索。为了解决这个问题，我们将焦点从传统的深度图预测转移到称为分层深度图像（LDI）的特定数据表示的回归，其包含关于参考帧中的遮挡区域的信息，并且可以填充遮挡间隙。小视角变化。我们提出了一种基于卷积神经网络（CNN）的新方法，以联合预测深度图和前景分离掩模，用于调节生成性对抗网络（GAN），以便在最初被遮挡的区域产生幻觉似是而非的颜色和深度。我们从单个图像中证明了我们的方法对新颖场景视图合成的有效性。

##### URL
[https://arxiv.org/abs/1807.08776](https://arxiv.org/abs/1807.08776)

##### PDF
[https://arxiv.org/pdf/1807.08776](https://arxiv.org/pdf/1807.08776)

