---
layout: post
title: "Muon Trigger for Mobile Phones"
date: 2017-09-25 17:15:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Maxim Borisyak, Michail Usvyatsov, Michael Mulhearn, Chase Shimmin, Andrey Ustyuzhanin
mathjax: true
---

* content
{:toc}

##### Abstract
The CRAYFIS experiment proposes to use privately owned mobile phones as a ground detector array for Ultra High Energy Cosmic Rays. Upon interacting with Earth's atmosphere, these events produce extensive particle showers which can be detected by cameras on mobile phones. A typical shower contains minimally-ionizing particles such as muons. As these particles interact with CMOS image sensors, they may leave tracks of faintly-activated pixels that are sometimes hard to distinguish from random detector noise. Triggers that rely on the presence of very bright pixels within an image frame are not efficient in this case. We present a trigger algorithm based on Convolutional Neural Networks which selects images containing such tracks and are evaluated in a lazy manner: the response of each successive layer is computed only if activation of the current layer satisfies a continuation criterion. Usage of neural networks increases the sensitivity considerably comparable with image thresholding, while the lazy evaluation allows for execution of the trigger under the limited computational power of mobile phones.

##### Abstract (translated by Google)
CRAYFIS实验建议使用私人拥有的移动电话作为超高能量宇宙射线的地面探测器阵列。在与地球大气层相互作用后，这些事件会产生广泛的微粒阵雨，这些微阵雨可以通过手机上的相机检测到。一个典型的淋浴包含最低限度的电离粒子，如μ子。由于这些粒子与CMOS图像传感器相互作用，它们可能留下微弱激活像素的轨迹，有时难以区分随机检测器噪声。在这种情况下，依赖图像帧中非常明亮像素的触发器效率不高。我们提出了一种基于卷积神经网络的触发算法，该算法选择包含这样的轨迹的图像，并且以懒惰的方式进行评估：仅当当前层的激活满足延续标准时才计算每个连续层的响应。神经网络的使用增加了与图像阈值相当的灵敏度，而懒惰的评估允许在手​​机有限的计算能力下执行触发。

##### URL
[https://arxiv.org/abs/1709.08605](https://arxiv.org/abs/1709.08605)

##### PDF
[https://arxiv.org/pdf/1709.08605](https://arxiv.org/pdf/1709.08605)

