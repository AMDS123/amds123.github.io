---
layout: post
title: "Hand Keypoint Detection in Single Images using Multiview Bootstrapping"
date: 2017-04-25 17:37:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Tomas Simon, Hanbyul Joo, Iain Matthews, Yaser Sheikh
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach that uses a multi-camera system to train fine-grained detectors for keypoints that are prone to occlusion, such as the joints of a hand. We call this procedure multiview bootstrapping: first, an initial keypoint detector is used to produce noisy labels in multiple views of the hand. The noisy detections are then triangulated in 3D using multiview geometry or marked as outliers. Finally, the reprojected triangulations are used as new labeled training data to improve the detector. We repeat this process, generating more labeled data in each iteration. We derive a result analytically relating the minimum number of views to achieve target true and false positive rates for a given detector. The method is used to train a hand keypoint detector for single images. The resulting keypoint detector runs in realtime on RGB images and has accuracy comparable to methods that use depth sensors. The single view detector, triangulated over multiple views, enables 3D markerless hand motion capture with complex object interactions.

##### Abstract (translated by Google)
我们提出了一种使用多摄像机系统的方法来训练对于易于闭塞的关键点（例如手的关节）的细粒度检测器。我们将这个过程称为多视图自举：首先，使用初始关键点检测器在手的多个视图中产生有噪声的标签。然后使用多视图几何体以三维方式对噪声检测进行三角化，或标记为异常值。最后，重新投影的三角形被用作新的标记的训练数据以改进检测器。我们重复这个过程，在每次迭代中生成更多的标记数据。我们从分析结果的角度出发，给出了一个给定的探测器实现目标真实和误报率的最小视图数量的结果。该方法用于训练单个图像的手部关键点检测器。由此产生的关键点检测器在RGB图像上实时运行，并具有与使用深度传感器的方法相媲美的精度。单视图检测器在多个视图上进行三角测量，可以实现3D无标记手部运动捕捉，并实现复杂的对象交互。

##### URL
[https://arxiv.org/abs/1704.07809](https://arxiv.org/abs/1704.07809)

##### PDF
[https://arxiv.org/pdf/1704.07809](https://arxiv.org/pdf/1704.07809)

