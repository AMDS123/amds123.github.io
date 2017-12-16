---
layout: post
title: "MegDet: A Large Mini-Batch Object Detector"
date: 2017-11-21 03:11:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Chao Peng, Tete Xiao, Zeming Li, Yuning Jiang, Xiangyu Zhang, Kai Jia, Gang Yu, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
The improvements in recent CNN-based object detection works, from R-CNN [11] and Fast/Faster R-CNN [10, 29] to recent Mask R-CNN [14] and RetinaNet [22], mainly come from new network, or framework, or loss design. But mini-batch size, a key factor in the training, has not been well studied. In this paper, we propose a Large Mini-Batch Object Detector (MegDet) to enable the training with much larger mini-batch size than before (e.g. from 16 to 256), so that we can effectively utilize multiple GPUs (up to 128 in our experiments) to significantly shorten the training time. Technically, we suggest a learning rate policy and Cross- GPU Batch Normalization, which together allow us to suc- cessfully train a large mini-batch detector in much less time (e.g., from 33 hours to 4 hours), and achieve even better accuracy. The MegDet is the backbone of our submission (mmAP 52.5%) to COCO 2017 Challenge, where we won the 1st place of Detection task.

##### Abstract (translated by Google)
从R-CNN [11]和Fast / Faster R-CNN [10,29]到最近的Mask R-CNN [14]和RetinaNet [22]，最近基于CNN的对象检测工作的改进主要来自新网络或框架或损失设计。但是，小批量培训的关键因素还没有得到很好的研究。在本文中，我们提出了一种大型小批量物体检测器（MegDet），可以实现比以前更大的小批量（例如从16到256）的训练，以便我们可以有效地利用多个GPU（高达128我们的实验）显着缩短训练时间。从技术上讲，我们提出了一个学习速率策略和跨GPU批量标准化，它们使我们能够在更短的时间内（例如从33小时到4小时）成功培训一个大型的小批量检测器，并获得更好的精度。 MegDet是我们提交给COCO 2017挑战赛的主要参赛者（mmAP 52.5％），在那里我们赢得了第一名的检测任务。

##### URL
[https://arxiv.org/abs/1711.07240](https://arxiv.org/abs/1711.07240)

##### PDF
[https://arxiv.org/pdf/1711.07240](https://arxiv.org/pdf/1711.07240)

