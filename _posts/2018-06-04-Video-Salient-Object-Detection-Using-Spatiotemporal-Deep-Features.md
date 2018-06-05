---
layout: post
title: "Video Salient Object Detection Using Spatiotemporal Deep Features"
date: 2018-06-04 06:45:14
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Segmentation Detection Relation
author: Trung-Nghia Le, Akihiro Sugimoto
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method for detecting salient objects in videos where temporal information in addition to spatial information is fully taken into account. Following recent reports on the advantage of deep features over conventional hand-crafted features, we propose a new set of SpatioTemporal Deep (STD) features that utilize local and global contexts over frames. We also propose new SpatioTemporal Conditional Random Field (STCRF) to compute saliency from STD features. STCRF is our extension of CRF to the temporal domain and describes the relationships among neighboring regions both in a frame and over frames. STCRF leads to temporally consistent saliency maps over frames, contributing to the accurate detection of salient objects' boundaries and noise reduction during detection. Our proposed method first segments an input video into multiple scales and then computes a saliency map at each scale level using STD features with STCRF. The final saliency map is computed by fusing saliency maps at different scale levels. Our experiments, using publicly available benchmark datasets, confirm that the proposed method significantly outperforms state-of-the-art methods. We also applied our saliency computation to the video object segmentation task, showing that our method outperforms existing video object segmentation methods.

##### Abstract (translated by Google)
本文介绍了一种用于检测视频中的突出对象的方法，其中除了空间信息之外的时间信息被充分考虑。继最近关于深度特征优于传统手工特征的报道之后，我们提出了一组新的SpatioTemporal Deep（STD）特征，这些特征利用了帧的局部和全局上下文。我们还提出了新的时空条件随机场（STCRF）来计算STD特征的显着性。 STCRF是我们将CRF扩展到时域并且描述帧和帧之间的相邻区域之间的关系。 STCRF可以在帧上产生时间一致的显着图，有助于在检测过程中精确检测显着物体的边界和降噪。我们提出的方法首先将输入视频分割成多个比例，然后使用STCRF的STD特征计算每个比例级别的显着图。通过融合不同比例级别的显着图来计算最终显着图。我们使用公开可用的基准数据集进行的实验证实，所提出的方法明显优于最先进的方法。我们还将显着性计算应用于视频对象分割任务，表明我们的方法优于现有的视频对象分割方法。

##### URL
[http://arxiv.org/abs/1708.01447](http://arxiv.org/abs/1708.01447)

##### PDF
[http://arxiv.org/pdf/1708.01447](http://arxiv.org/pdf/1708.01447)

