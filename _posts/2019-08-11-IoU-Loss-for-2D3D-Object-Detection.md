---
layout: post
title: "IoU Loss for 2D/3D Object Detection"
date: 2019-08-11 04:19:25
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Dingfu Zhou, Jin Fang, Xibin Song, Chenye Guan, Junbo Yin, Yuchao Dai, Ruigang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In 2D/3D object detection task, Intersection-over-Union (IoU) has been widely employed as an evaluation metric to evaluate the performance of different detectors in the testing stage. However, during the training stage, the common distance loss (\eg, $L_1$ or $L_2$) is often adopted as the loss function to minimize the discrepancy between the predicted and ground truth Bounding Box (Bbox). To eliminate the performance gap between training and testing, the IoU loss has been introduced for 2D object detection in \cite{yu2016unitbox} and \cite{rezatofighi2019generalized}. Unfortunately, all these approaches only work for axis-aligned 2D Bboxes, which cannot be applied for more general object detection task with rotated Bboxes. To resolve this issue, we investigate the IoU computation for two rotated Bboxes first and then implement a unified framework, IoU loss layer for both 2D and 3D object detection tasks. By integrating the implemented IoU loss into several state-of-the-art 3D object detectors, consistent improvements have been achieved for both bird-eye-view 2D detection and point cloud 3D detection on the public KITTI benchmark.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.03851](https://arxiv.org/abs/1908.03851)

##### PDF
[https://arxiv.org/pdf/1908.03851](https://arxiv.org/pdf/1908.03851)

