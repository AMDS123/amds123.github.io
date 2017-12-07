---
layout: post
title: "Video Salient Object Detection Using Spatiotemporal Deep Features"
date: 2017-08-04 11:05:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Trung-Nghia Le, Akihiro Sugimoto
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method for detecting salient objects in videos where temporal information in addition to spatial information is fully taken into account. Following recent reports on the advantage of deep features over conventional hand-crafted features, we propose the SpatioTemporal Deep (STD) feature that utilizes local and global contexts over frames. We also propose the SpatioTemporal Conditional Random Field (STCRF) to compute saliency from STD features. STCRF is our extension of CRF toward the temporal domain and formulates the relationship between neighboring regions both in a frame and over frames. STCRF leads to temporally consistent saliency maps over frames, contributing to the accurate detection of the boundaries of salient objects and the reduction of noise in detection. Our proposed method first segments an input video into multiple scales and then computes a saliency map at each scale level using STD features with STCRF. The final saliency map is computed by fusing saliency maps at different scale levels. Our intensive experiments using publicly available benchmark datasets confirm that the proposed method significantly outperforms state-of-the-art methods. We also applied our saliency computation to the video object segmentation task, showing that our method outperforms existing video object segmentation methods.

##### Abstract (translated by Google)
本文提出了一种检测视频中除了空间信息之外的时间信息被充分考虑的显着对象的方法。在最近有关深度特征优于传统手工特征的报道之后，我们提出了空间深度（STD）特征，该特征利用了帧的局部和全局上下文。我们还提出了时空条件随机场（STCRF）来计算STD特征的显着性。 STCRF是我们将CRF扩展到时间域，并在帧和帧之间制定相邻区域之间的关系。 STCRF在帧上产生时间上一致的显着图，有助于精确检测显着物体的边界和减少检测中的噪声。我们提出的方法首先将输入视频分割成多个比例，然后使用STCRF的STD特征计算每个比例级别的显着图。最终的显着图是通过融合不同尺度水平的显着图来计算的。我们使用公开可用的基准数据集的密集实验证实，所提出的方法明显优于最先进的方法。我们还将显着性计算应用于视频对象分割任务，表明我们的方法优于现有的视频对象分割方法。

##### URL
[https://arxiv.org/abs/1708.01447](https://arxiv.org/abs/1708.01447)

##### PDF
[https://arxiv.org/pdf/1708.01447](https://arxiv.org/pdf/1708.01447)

