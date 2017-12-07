---
layout: post
title: "Robust 3D Action Recognition through Sampling Local Appearances and Global Distributions"
date: 2017-12-04 14:31:42
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Detection Recognition
author: Mengyuan Liu, Hong Liu, Chen Chen
mathjax: true
---

* content
{:toc}

##### Abstract
3D action recognition has broad applications in human-computer interaction and intelligent surveillance. However, recognizing similar actions remains challenging since previous literature fails to capture motion and shape cues effectively from noisy depth data. In this paper, we propose a novel two-layer Bag-of-Visual-Words (BoVW) model, which suppresses the noise disturbances and jointly encodes both motion and shape cues. First, background clutter is removed by a background modeling method that is designed for depth data. Then, motion and shape cues are jointly used to generate robust and distinctive spatial-temporal interest points (STIPs): motion-based STIPs and shape-based STIPs. In the first layer of our model, a multi-scale 3D local steering kernel (M3DLSK) descriptor is proposed to describe local appearances of cuboids around motion-based STIPs. In the second layer, a spatial-temporal vector (STV) descriptor is proposed to describe the spatial-temporal distributions of shape-based STIPs. Using the Bag-of-Visual-Words (BoVW) model, motion and shape cues are combined to form a fused action representation. Our model performs favorably compared with common STIP detection and description methods. Thorough experiments verify that our model is effective in distinguishing similar actions and robust to background clutter, partial occlusions and pepper noise.

##### Abstract (translated by Google)
三维动作识别在人机交互和智能监控方面有着广泛的应用。然而，认识到类似的行为仍然具有挑战性，因为以前的文献无法有效地从噪音深度数据中捕捉运动和形成线索。在本文中，我们提出了一种新的视觉单词袋（BoVW）模型，它抑制了噪声干扰并共同编码运动和形状线索。首先，通过为深度数据设计的背景建模方法去除背景杂波。然后，运动和形状线索共同用于生成强健和独特的时空兴趣点（STIPs）：基于运动的STIPs和基于形状的STIPs。在我们模型的第一层，提出了一个多尺度三维局部控制核（M3DLSK）描述符来描述基于运动的STIP周围的长方体的局部外观。在第二层中，提出了时空矢量（STV）描述符来描述基于形状的STIP的空间 - 时间分布。使用Bag-of-Visual-Words（BoVW）模型，运动和形状线索被组合以形成融合的动作表示。与普通的STIP检测和描述方法相比，我们的模型性能更好。彻底的实验验证了我们的模型在区分相似动作和鲁棒背景杂波，部分遮挡和胡椒噪声方面是有效的。

##### URL
[http://arxiv.org/abs/1712.01090](http://arxiv.org/abs/1712.01090)

##### PDF
[http://arxiv.org/pdf/1712.01090](http://arxiv.org/pdf/1712.01090)

