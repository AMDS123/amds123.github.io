---
layout: post
title: "An Occlusion Reasoning Scheme for Monocular Pedestrian Tracking in Dynamic Scenes"
date: 2015-01-25 08:38:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Optimization Detection
author: Sourav Garg, Swagat Kumar, Rajesh Ratnakaram, Prithwijit Guha
mathjax: true
---

* content
{:toc}

##### Abstract
This paper looks into the problem of pedestrian tracking using a monocular, potentially moving, uncalibrated camera. The pedestrians are located in each frame using a standard human detector, which are then tracked in subsequent frames. This is a challenging problem as one has to deal with complex situations like changing background, partial or full occlusion and camera motion. In order to carry out successful tracking, it is necessary to resolve associations between the detected windows in the current frame with those obtained from the previous frame. Compared to methods that use temporal windows incorporating past as well as future information, we attempt to make decision on a frame-by-frame basis. An occlusion reasoning scheme is proposed to resolve the association problem between a pair of consecutive frames by using an affinity matrix that defines the closeness between a pair of windows and then, uses a binary integer programming to obtain unique association between them. A second stage of verification based on SURF matching is used to deal with those cases where the above optimization scheme might yield wrong associations. The efficacy of the approach is demonstrated through experiments on several standard pedestrian datasets.

##### Abstract (translated by Google)
本文探讨了使用单眼，可能移动，未校准的相机的行人跟踪问题。行人通过标准的人体探测器定位在每一帧中，然后在随后的帧中进行跟踪。这是一个具有挑战性的问题，因为人们必须处理复杂的情况，如改变背景，部分或全部遮挡和摄像机运动。为了执行成功的跟踪，有必要解决在当前帧中检测到的窗口与从前一帧中获得的窗口之间的关联。与使用包含过去和未来信息的时间窗口的方法相比，我们试图在逐帧的基础上做出决定。提出了一种遮挡推理方案，通过使用定义一对窗口之间的紧密度的相关矩阵来解决一对连续帧之间的关联问题，然后使用二进制整数规划来获得它们之间的唯一关联。基于SURF匹配的第二阶段验证用于处理上述优化方案可能产生错误关联的情况。该方法的功效通过在几个标准的行人数据集上的实验来证明。

##### URL
[https://arxiv.org/abs/1501.06129](https://arxiv.org/abs/1501.06129)

##### PDF
[https://arxiv.org/pdf/1501.06129](https://arxiv.org/pdf/1501.06129)

