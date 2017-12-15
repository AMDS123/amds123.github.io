---
layout: post
title: "Learning to track for spatio-temporal action localization"
date: 2015-09-27 11:21:16
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection
author: Philippe Weinzaepfel, Zaid Harchaoui, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an effective approach for spatio-temporal action localization in realistic videos. The approach first detects proposals at the frame-level and scores them with a combination of static and motion CNN features. It then tracks high-scoring proposals throughout the video using a tracking-by-detection approach. Our tracker relies simultaneously on instance-level and class-level detectors. The tracks are scored using a spatio-temporal motion histogram, a descriptor at the track level, in combination with the CNN features. Finally, we perform temporal localization of the action using a sliding-window approach at the track level. We present experimental results for spatio-temporal localization on the UCF-Sports, J-HMDB and UCF-101 action localization datasets, where our approach outperforms the state of the art with a margin of 15%, 7% and 12% respectively in mAP.

##### Abstract (translated by Google)
我们提出了一个有效的方法来实现现实视频中的时空动作定位。该方法首先检测框架级别的提案，并使用静态和动态CNN功能的组合对它们进行评分。然后使用逐行检测的方法跟踪整个视频中的高分计划。我们的跟踪器同时依赖于实例级别和类别级别的检测器。使用空间 - 时间运动直方图，在轨道级的描述符，结合CNN特征对轨道进行评分。最后，我们使用滑动窗口方法在轨道级别执行动作的时间定位。我们在UCF-Sports，J-HMDB和UCF-101动作定位数据集上给出了时空定位的实验结果，在这些数据集中，我们的方法的性能优于现有技术，在mAP中分别为15％，7％和12％ 。

##### URL
[https://arxiv.org/abs/1506.01929](https://arxiv.org/abs/1506.01929)

##### PDF
[https://arxiv.org/pdf/1506.01929](https://arxiv.org/pdf/1506.01929)

