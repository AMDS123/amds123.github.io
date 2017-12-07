---
layout: post
title: "An Efficient Approach for Object Detection and Tracking of Objects in a Video with Variable Background"
date: 2017-05-11 08:23:35
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Kumar S. Ray, Soma Chakraborty
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel approach to create an automated visual surveillance system which is very efficient in detecting and tracking moving objects in a video captured by moving camera without any apriori information about the captured scene. Separating foreground from the background is challenging job in videos captured by moving camera as both foreground and background information change in every consecutive frames of the image sequence; thus a pseudo-motion is perceptive in background. In the proposed algorithm, the pseudo-motion in background is estimated and compensated using phase correlation of consecutive frames based on the principle of Fourier shift theorem. Then a method is proposed to model an acting background from recent history of commonality of the current frame and the foreground is detected by the differences between the background model and the current frame. Further exploiting the recent history of dissimilarities of the current frame, actual moving objects are detected in the foreground. Next, a two-stepped morphological operation is proposed to refine the object region for an optimum object size. Each object is attributed by its centroid, dimension and three highest peaks of its gray value histogram. Finally, each object is tracked using Kalman filter based on its attributes. The major advantage of this algorithm over most of the existing object detection and tracking algorithms is that, it does not require initialization of object position in the first frame or training on sample data to perform. Performance of the algorithm is tested on benchmark videos containing variable background and very satisfiable results is achieved. The performance of the algorithm is also comparable with some of the state-of-the-art algorithms for object detection and tracking.

##### Abstract (translated by Google)
本文提出了一种新颖的方法来创建一个自动化的视觉监控系统，这是非常有效的检测和跟踪移动相机拍摄的视频中的移动物体，没有任何关于捕获的场景的先验信息。从背景中分离前景对于通过移动相机拍摄的视频来说是具有挑战性的工作，因为前景和背景信息在图像序列的每个连续帧中都改变;因此伪运动在背景中是感知的。在所提出的算法中，基于傅里叶移位定理的原理，利用连续帧的相位相关来估计和补偿背景中的伪运动。然后提出了一种基于当前帧的通用性近期历史的背景模型，并通过背景模型与当前帧之间的差异来检测前景。进一步利用当前帧的近期历史不同，在前景中检测实际的运动物体。接下来，提出了两步形态学操作来改善对象区域的最佳对象大小。每个对象都由它的质心，维度和灰度值直方图的三个最高峰值来归属。最后，使用基于其属性的卡尔曼滤波器来跟踪每个对象。这种算法的主要优势在于大部分现有的物体检测和跟踪算法，它不需要初始化第一帧中的物体位置或者训练样本数据来执行。在包含可变背景的基准视频上测试算法的性能，并且实现了非常令人满意的结果。该算法的性能也与用于物体检测和跟踪的一些最先进的算法相当。

##### URL
[https://arxiv.org/abs/1706.02672](https://arxiv.org/abs/1706.02672)

##### PDF
[https://arxiv.org/pdf/1706.02672](https://arxiv.org/pdf/1706.02672)

