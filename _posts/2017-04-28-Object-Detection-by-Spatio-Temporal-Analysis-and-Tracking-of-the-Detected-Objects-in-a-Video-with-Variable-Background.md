---
layout: post
title: "Object Detection by Spatio-Temporal Analysis and Tracking of the Detected Objects in a Video with Variable Background"
date: 2017-04-28 09:32:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Kumar S. Ray, Vijayan K. Asari, Soma Chakraborty
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a novel approach for detecting and tracking objects in videos with variable background i.e. videos captured by moving cameras without any additional sensor. In a video captured by a moving camera, both the background and foreground are changing in each frame of the image sequence. So for these videos, modeling a single background with traditional background modeling methods is infeasible and thus the detection of actual moving object in a variable background is a challenging task. To detect actual moving object in this work, spatio-temporal blobs have been generated in each frame by spatio-temporal analysis of the image sequence using a three-dimensional Gabor filter. Then individual blobs, which are parts of one object are merged using Minimum Spanning Tree to form the moving object in the variable background. The height, width and four-bin gray-value histogram of the object are calculated as its features and an object is tracked in each frame using these features to generate the trajectories of the object through the video sequence. In this work, problem of data association during tracking is solved by Linear Assignment Problem and occlusion is handled by the application of kalman filter. The major advantage of our method over most of the existing tracking algorithms is that, the proposed method does not require initialization in the first frame or training on sample data to perform. Performance of the algorithm has been tested on benchmark videos and very satisfactory result has been achieved. The performance of the algorithm is also comparable and superior with respect to some benchmark algorithms.

##### Abstract (translated by Google)
在本文中，我们提出了一种新颖的方法，用于检测和跟踪具有可变背景的视频中的对象，即通过移动相机捕获的视频而不需要任何额外的传感器在由移动照相机拍摄的视频中，背景和前景在图像序列的每个帧中都变化。所以对于这些视频来说，用传统的背景建模方法建模一个背景是不可行的，因此在可变背景中检测实际的运动对象是一项具有挑战性的任务。为了在本文中检测实际的运动对象，通过使用三维Gabor滤波器对图像序列进行时空分析，在每帧中生成时空斑点。然后使用最小生成树合并作为一个对象的一部分的单个斑点，以在可变背景中形成移动对象。计算物体的高度，宽度和四仓灰度直方图作为其特征，并利用这些特征在每一帧中跟踪物体以通过视频序列生成物体的轨迹。在这项工作中，跟踪过程中的数据关联问题通过线性分配问题来解决，而遮挡则由卡尔曼滤波器的应用来处理。我们的方法相对于现有的大多数跟踪算法的主要优点是，所提出的方法不需要在第一帧中进行初始化或者对样本数据进行训练。该算法的性能已经通过基准视频测试，取得了非常满意的结果。该算法的性能也相对于一些基准算法具有可比性和优越性。

##### URL
[https://arxiv.org/abs/1705.02949](https://arxiv.org/abs/1705.02949)

