---
layout: post
title: "Improving Multiple Object Tracking with Optical Flow and Edge Preprocessing"
date: 2018-01-29 17:42:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Tracking Object_Tracking Detection
author: David-Alexandre Beaupr&#xe9;, Guillaume-Alexandre Bilodeau, Nicolas Saunier
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a new method for detecting road users in an urban environment which leads to an improvement in multiple object tracking. Our method takes as an input a foreground image and improves the object detection and segmentation. This new image can be used as an input to trackers that use foreground blobs from background subtraction. The first step is to create foreground images for all the frames in an urban video. Then, starting from the original blobs of the foreground image, we merge the blobs that are close to one another and that have similar optical flow. The next step is extracting the edges of the different objects to detect multiple objects that might be very close (and be merged in the same blob) and to adjust the size of the original blobs. At the same time, we use the optical flow to detect occlusion of objects that are moving in opposite directions. Finally, we make a decision on which information we keep in order to construct a new foreground image with blobs that can be used for tracking. The system is validated on four videos of an urban traffic dataset. Our method improves the recall and precision metrics for the object detection task compared to the vanilla background subtraction method and improves the CLEAR MOT metrics in the tracking tasks for most videos.

##### Abstract (translated by Google)
在本文中，我们提出了一种在城市环境中检测道路使用者的新方法，这导致多目标跟踪的改进。我们的方法将前景图像作为输入，改进了对象检测和分割。这个新的图像可以用作输入到使用来自背景扣除的前景斑点的跟踪器。第一步是为城市视频中的所有帧创建前景图像。然后，从前景图像的原始斑点开始，我们合并彼此接近且具有相似光流的斑点。下一步是提取不同对象的边缘，以检测可能非常接近的多个对象（并将其合并到同一个Blob中），并调整原始Blob的大小。同时，我们使用光流来检测在相反方向移动的物体的遮挡。最后，我们决定使用哪些信息来构建一个新的可用于跟踪的斑点的前景图像。该系统在城市交通数据集的四个视频中被验证。与香草背景减法相比，我们的方法提高了对象检测任务的查全率和精度度量，并且改善了大多数视频的跟踪任务中的CLEAR MOT度量。

##### URL
[http://arxiv.org/abs/1801.09646](http://arxiv.org/abs/1801.09646)

##### PDF
[http://arxiv.org/pdf/1801.09646](http://arxiv.org/pdf/1801.09646)

