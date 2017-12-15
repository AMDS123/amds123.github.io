---
layout: post
title: "Seeing Invisible Poses: Estimating 3D Body Pose from Egocentric Video"
date: 2016-03-24 21:46:49
categories: arXiv_CV
tags: arXiv_CV Video_Caption Face Deep_Learning Prediction
author: Hao Jiang, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding the camera wearer's activity is central to egocentric vision, yet one key facet of that activity is inherently invisible to the camera--the wearer's body pose. Prior work focuses on estimating the pose of hands and arms when they come into view, but this 1) gives an incomplete view of the full body posture, and 2) prevents any pose estimate at all in many frames, since the hands are only visible in a fraction of daily life activities. We propose to infer the "invisible pose" of a person behind the egocentric camera. Given a single video, our efficient learning-based approach returns the full body 3D joint positions for each frame. Our method exploits cues from the dynamic motion signatures of the surrounding scene--which changes predictably as a function of body pose--as well as static scene structures that reveal the viewpoint (e.g., sitting vs. standing). We further introduce a novel energy minimization scheme to infer the pose sequence. It uses soft predictions of the poses per time instant together with a non-parametric model of human pose dynamics over longer windows. Our method outperforms an array of possible alternatives, including deep learning approaches for direct pose regression from images.

##### Abstract (translated by Google)
了解相机佩戴者的活动是以自我为中心的视觉的中心，然而，该活动的一个关键方面是相机本身不可见的 - 佩戴者的身体姿势。以前的工作重点是估计手和手臂的姿势，当他们进入视野时，但是这1）给出了全身姿态的不完整视图，并且2）在许多帧中完全防止任何姿态估计，因为手只是可见的在日常生活活动的一小部分。我们建议推断自我中心相机背后的一个人的“看不见的姿势”。给定一个视频，我们高效的基于学习的方法返回每个帧的全身三维联合位置。我们的方法利用来自周围场景的动态运动特征（其可预测地作为身体姿态的函数）以及揭示视点的静态场景结构（例如，坐与站）的线索。我们进一步引入一种新的能量最小化方案来推断姿态序列。它使用每个时间瞬间的姿势的软预测以及在较长的窗口上的人体姿态动态的非参数模型。我们的方法胜过了一系列可能的选择，包括从图像直接进行姿态回归的深度学习方法。

##### URL
[https://arxiv.org/abs/1603.07763](https://arxiv.org/abs/1603.07763)

##### PDF
[https://arxiv.org/pdf/1603.07763](https://arxiv.org/pdf/1603.07763)

