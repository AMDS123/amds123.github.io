---
layout: post
title: "UAV Visual Teach and Repeat Using Only Semantic Object Features"
date: 2018-01-24 08:09:41
categories: arXiv_RO
tags: arXiv_RO Object_Detection Face Detection SLAM
author: Amirmasoud Ghasemi Toudeshki, Faraz Shamshirdar, Richard Vaughan
mathjax: true
---

* content
{:toc}

##### Abstract
We demonstrate the use of semantic object detections as robust features for Visual Teach and Repeat (VTR). Recent CNN-based object detectors are able to reliably detect objects of tens or hundreds of categories in a video at frame rates. We show that such detections are repeatable enough to use as landmarks for VTR, without any low-level image features. Since object detections are highly invariant to lighting and surface appearance changes, our VTR can cope with global lighting changes and local movements of the landmark objects. In the teaching phase, we build a series of compact scene descriptors: a list of detected object labels and their image-plane locations. In the repeating phase, we use Seq-SLAM-like relocalization to identify the most similar learned scene, then use a motion control algorithm based on the funnel lane theory to navigate the robot along the previously piloted trajectory. We evaluate the method on a commodity UAV, examining the robustness of the algorithm to new viewpoints, lighting conditions, and movements of landmark objects. The results suggest that semantic object features could be useful due to their invariance to superficial appearance changes compared to low-level image features.

##### Abstract (translated by Google)
我们演示了使用语义对象检测作为可视化教学和重复（VTR）的强大功能。最近的基于CNN的物体检测器能够以帧率在视频中可靠地检测数十或数百个类别的物体。我们表明，这种检测是足够可重复使用的录像机的地标，没有任何低级别的图像功能。由于物体检测对光照和表面外观的变化高度不变，因此我们的VTR可以应对全球照明变化和地标物体的局部移动。在教学阶段，我们建立了一系列紧凑的场景描述符：检测到的对象标签列表及其图像平面位置。在重复阶段，我们使用类似于Seq-SLAM的重定位来识别最相似的学习场景，然后使用基于漏斗道理论的运动控制算法沿着先前导航的轨迹导航机器人。我们评估商品无人机的方法，检查算法的鲁棒性，以新的观点，照明条件和地标对象的运动。结果表明，与低级图像特征相比，语义对象特征可能是有用的，因为它们对表面外观变化的不变性。

##### URL
[http://arxiv.org/abs/1801.07899](http://arxiv.org/abs/1801.07899)

##### PDF
[http://arxiv.org/pdf/1801.07899](http://arxiv.org/pdf/1801.07899)

