---
layout: post
title: "Pack and Detect: Fast Object Detection in Videos Using Region-of-Interest Packing"
date: 2018-09-05 19:29:34
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Summarization Tracking Object_Tracking Detection Relation
author: Athindran Ramesh Kumar, Balaraman Ravindran, Anand Raghunathan
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection in videos is an important task in computer vision for various applications such as object tracking, video summarization and video search. Although great progress has been made in improving the accuracy of object detection in recent years due to improved techniques for training and deploying deep neural networks, they are computationally very intensive. For example, processing a video at 300x300 resolution using the SSD300 (Single Shot Detector) object detection network with VGG16 as backbone at 30 fps requires 1.87 trillion FLOPS/s. In order to address this challenge, we make two important observations in the context of videos. In some scenarios, most of the regions in a video frame are background and the salient objects occupy only a small fraction of the area in the frame. Further, in a video, there is a strong temporal correlation between consecutive frames. Based on these observations, we propose Pack and Detect (PaD) to reduce the computational requirements for the task of object detection in videos using neural networks. In PaD, the input video frame is processed at full size in selected frames called anchor frames. In the frames between the anchor frames, namely inter-anchor frames, the regions of interest(ROI) are identified based on the detections in the previous frame. We propose an algorithm to pack the ROI's of each inter-anchor frame together in a lower sized frame. In order to maintain the accuracy of object detection, the proposed algorithm expands the ROI's greedily to provide more background information to the detector. The computational requirements are reduced due to the lower size of the input. This method can potentially reduce the number of FLOPS required for a frame by 4x. Tuning the algorithm parameters can provide a 1.3x increase in throughput with only a 2.5% drop in accuracy.

##### Abstract (translated by Google)
视频中的对象检测是计算机视觉中的重要任务，用于各种应用，例如对象跟踪，视频摘要和视频搜索。尽管近年来由于改进的训练和部署深度神经网络技术在提高物体检测精度方面取得了很大进展，但它们在计算上非常密集。例如，使用SSD300（单击检测器）物体检测网络以300x300分辨率处理视频，其中VGG16为30 fps的主干，需要1.87万亿FLOPS / s。为了应对这一挑战，我们在视频背景下提出了两个重要的观察结果。在一些场景中，视频帧中的大多数区域是背景，并且显着对象仅占据帧中区域的一小部分。此外，在视频中，在连续帧之间存在强时间相关性。基于这些观察，我们提出了打包和检测（PaD），以减少使用神经网络的视频中对象检测任务的计算要求。在PaD中，输入视频帧在称为锚帧的所选帧中以全尺寸处理。在锚帧之间的帧中，即帧间锚帧，基于前一帧中的检测来识别感兴趣区域（ROI）。我们提出了一种算法，将每个帧间锚帧的ROI打包在一个较小的帧中。为了保持物体检测的准确性，该算法贪婪地扩展了ROI，为探测器提供了更多的背景信息。由于输入的较小尺寸，计算要求降低。此方法可以将帧所需的FLOPS数量减少4倍。调整算法参数可以使吞吐量提高1.3倍，精度仅下降2.5％。

##### URL
[http://arxiv.org/abs/1809.01701](http://arxiv.org/abs/1809.01701)

##### PDF
[http://arxiv.org/pdf/1809.01701](http://arxiv.org/pdf/1809.01701)

