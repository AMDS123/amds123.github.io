---
layout: post
title: "PatchFCN for Intracranial Hemorrhage Detection"
date: 2018-06-08 16:28:05
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Weicheng Kuo, Christian H&#xe4;ne, Esther Yuh, Pratik Mukherjee, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the problem of detecting acute intracranial hemorrhage on head computed tomography (CT) scans. We formulate it as a pixel-wise labeling task of the frames that constitute a single head scan. The standard approach for this task is the fully convolutional network (FCN) which runs on the whole image at both training and test time. We propose a patch-based approach that controls the amount of context available to the FCN, based on the observation that when radiologists are interpreting CT scans, their judgment depends primarily on local cues and does not require the whole image context. To develop and validate the system, we collected a pixel-wise labeled dataset of 591 scans that covers a wide range of hemorrhage types and imaging conditions in the real world. We show that no pretraining from natural images is needed. By aggregating the pixel-wise labeling, our system is able to make region-level, frame-level, and stack-level decisions. Our final system approaches an expert radiologist performance with a high average precision (AP) of 96.5 +/- 1.3 % for hemorrhage classification on stack level while running at 23ms per frame

##### Abstract (translated by Google)
本文研究了在头部CT扫描中检测急性颅内出血的问题。我们将其制定为构成单头扫描的帧的像素方式标记任务。这个任务的标准方法是完全卷积网络（FCN），它在训练和测试时间在整个图像上运行。我们提出了一种基于补丁的方法来控制FCN可用的上下文数量，基于观察结果，当放射科医师解释CT扫描时，他们的判断主要取决于局部提示，并且不需要整个图像上下文。为了开发和验证系统，我们收集了591个扫描的像素标记数据集，涵盖了现实世界中各种出血类型和成像条件。我们表明，不需要从自然图像进行预训练。通过聚合像素标签，我们的系统能够进行区域级，框架级和堆叠级决策。我们的最终系统接近专家放射科医师的表现，其平均精确度（AP）为96.5 +/- 1.3％，用于堆叠层面出血分类，同时以每帧23ms运行

##### URL
[http://arxiv.org/abs/1806.03265](http://arxiv.org/abs/1806.03265)

##### PDF
[http://arxiv.org/pdf/1806.03265](http://arxiv.org/pdf/1806.03265)

