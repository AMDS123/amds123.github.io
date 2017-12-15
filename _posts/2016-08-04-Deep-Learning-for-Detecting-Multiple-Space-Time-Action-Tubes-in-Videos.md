---
layout: post
title: "Deep Learning for Detecting Multiple Space-Time Action Tubes in Videos"
date: 2016-08-04 13:38:38
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning Detection
author: Suman Saha, Gurkirt Singh, Michael Sapienza, Philip H. S. Torr, Fabio Cuzzolin
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose an approach to the spatiotemporal localisation (detection) and classification of multiple concurrent actions within temporally untrimmed videos. Our framework is composed of three stages. In stage 1, appearance and motion detection networks are employed to localise and score actions from colour images and optical flow. In stage 2, the appearance network detections are boosted by combining them with the motion detection scores, in proportion to their respective spatial overlap. In stage 3, sequences of detection boxes most likely to be associated with a single action instance, called action tubes, are constructed by solving two energy maximisation problems via dynamic programming. While in the first pass, action paths spanning the whole video are built by linking detection boxes over time using their class-specific scores and their spatial overlap, in the second pass, temporal trimming is performed by ensuring label consistency for all constituting detection boxes. We demonstrate the performance of our algorithm on the challenging UCF101, J-HMDB-21 and LIRIS-HARL datasets, achieving new state-of-the-art results across the board and significantly increasing detection speed at test time. We achieve a huge leap forward in action detection performance and report a 20% and 11% gain in mAP (mean average precision) on UCF-101 and J-HMDB-21 datasets respectively when compared to the state-of-the-art.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个时空定位（检测）和时间未修剪的视频内的多个并发行动的分类方法。我们的框架由三个阶段组成。在阶段1中，采用外观和运动检测网络来定位和评估来自彩色图像和光流的动作。在阶段2中，外观网络检测通过将它们与运动检测分数组合，与它们各自的空间重叠成比例地被提升。在阶段3中，通过动态规划解决两个能量最大化问题来构建最有可能与单个动作实例相关联的检测框序列，称为动作管。在第一遍中，跨越整个视频的行动路径通过使用其特定类别分数和它们的空间重叠随时间链接检测框来建立。在第二遍中，通过确保所有构成检测框的标签一致性来执行时间修剪。我们演示了我们的算法在具有挑战性的UCF101，J-HMDB-21和LIRIS-HARL数据集上的性能，实现了全新的最先进的结果，并显着提高了测试时的检测速度。我们在行为检测性能方面实现了巨大的飞跃，与最先进的技术相比，分别报告了UCF-101和J-HMDB-21数据集上的mAP（平均平均精确度）的20％和11％的增长。

##### URL
[https://arxiv.org/abs/1608.01529](https://arxiv.org/abs/1608.01529)

##### PDF
[https://arxiv.org/pdf/1608.01529](https://arxiv.org/pdf/1608.01529)

