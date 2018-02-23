---
layout: post
title: "Driver Hand Localization and Grasp Analysis: A Vision-based Real-time Approach"
date: 2018-02-22 00:14:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Siddharth, Akshay Rangesh, Eshed Ohn-Bar, Mohan M. Trivedi
mathjax: true
---

* content
{:toc}

##### Abstract
Extracting hand regions and their grasp information from images robustly in real-time is critical for occupants' safety and in-vehicular infotainment applications. It must however, be noted that naturalistic driving scenes suffer from rapidly changing illumination and occlusion. This is aggravated by the fact that hands are highly deformable objects, and change in appearance frequently. This work addresses the task of accurately localizing driver hands and classifying the grasp state of each hand. We use a fast ConvNet to first detect likely hand regions. Next, a pixel-based skin classifier that takes into account the global illumination changes is used to refine the hand detections and remove false positives. This step generates a pixel-level mask for each hand. Finally, we study each such masked regions and detect if the driver is grasping the wheel, or in some cases a mobile phone. Through evaluation we demonstrate that our method can outperform state-of-the-art pixel based hand detectors, while running faster (at 35 fps) than other deep ConvNet based frameworks even for grasp analysis. Hand mask cues are shown to be crucial when analyzing a set of driver hand gestures (wheel/mobile phone grasp and no-grasp) in naturalistic driving settings. The proposed detection and localization pipeline hence can act as a general framework for real-time hand detection and gesture classification.

##### Abstract (translated by Google)
实时鲁棒地从图像中提取手部区域及其掌握信息对于居民的安全和车载信息娱乐应用至关重要。然而，必须指出的是，自然驾驶场景遭受快速变化的照明和遮挡。这是因为手是高度可变形的物体并且经常在外观上变化而加剧的。这项工作解决了准确定位驾驶员手和分类每只手的抓地力状态的任务。我们使用一个快速的ConvNet来首先检测可能的手区域。接下来，将考虑全局照明变化的基于像素的皮肤分类器用于优化手部检测并消除误报。这一步为每只手产生一个像素级掩模。最后，我们研究每个这样的遮蔽区域，并检测驾驶员是否抓住车轮，或者在某些情况下是手机。通过评估，我们证明了我们的方法可以超越最先进的基于像素的手持式检测器，而运行速度比其他基于深度ConvNet的框架更快（以35 fps），即使是掌握分析。在自然驾驶设置中分析一组驾驶员手势（车轮/手机抓握和不抓握）时，手部面罩线索显示为至关重要。所提出的检测和本地化流水线因此可以作为用于实时手部检测和手势分类的一般框架。

##### URL
[http://arxiv.org/abs/1802.07854](http://arxiv.org/abs/1802.07854)

##### PDF
[http://arxiv.org/pdf/1802.07854](http://arxiv.org/pdf/1802.07854)

