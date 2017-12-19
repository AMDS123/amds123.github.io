---
layout: post
title: "Coherent Motion Segmentation in Moving Camera Videos using Optical Flow Orientations"
date: 2015-11-05 06:10:13
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Manjunath Narayana, Allen Hanson, Erik Learned-Miller
mathjax: true
---

* content
{:toc}

##### Abstract
In moving camera videos, motion segmentation is commonly performed using the image plane motion of pixels, or optical flow. However, objects that are at different depths from the camera can exhibit different optical flows even if they share the same real-world motion. This can cause a depth-dependent segmentation of the scene. Our goal is to develop a segmentation algorithm that clusters pixels that have similar real-world motion irrespective of their depth in the scene. Our solution uses optical flow orientations instead of the complete vectors and exploits the well-known property that under camera translation, optical flow orientations are independent of object depth. We introduce a probabilistic model that automatically estimates the number of observed independent motions and results in a labeling that is consistent with real-world motion in the scene. The result of our system is that static objects are correctly identified as one segment, even if they are at different depths. Color features and information from previous frames in the video sequence are used to correct occasional errors due to the orientation-based segmentation. We present results on more than thirty videos from different benchmarks. The system is particularly robust on complex background scenes containing objects at significantly different depths

##### Abstract (translated by Google)
在移动摄像机视频时，通常使用像素的图像平面运动或光流来执行运动分割。但是，距相机不同深度的物体即使共享相同的现实运动，也可能呈现不同的光流。这可能导致场景的深度依赖性分割。我们的目标是开发一种分割算法，对具有相似真实世界运动的像素进行聚类，而不管场景中的深度如何。我们的解决方案使用光流取向而不是完整的矢量，并利用相机平移下的众所周知的性质，光流方向与对象深度无关。我们引入了一个概率模型，自动估计观察到的独立运动的数量，并导致与场景中的真实世界运动一致的标记。我们的系统的结果是静态对象被正确识别为一个段，即使它们在不同的深度。来自视频序列中前一帧的颜色特征和信息被用于校正由于基于方向的分割而引起的偶然错误。我们在不同基准的30多个视频中呈现结果。该系统在包含明显不同深度的对象的复杂背景场景中特别稳健

##### URL
[https://arxiv.org/abs/1511.01619](https://arxiv.org/abs/1511.01619)

##### PDF
[https://arxiv.org/pdf/1511.01619](https://arxiv.org/pdf/1511.01619)

