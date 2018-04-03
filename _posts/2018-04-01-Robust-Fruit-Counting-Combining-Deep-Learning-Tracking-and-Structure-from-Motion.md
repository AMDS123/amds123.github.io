---
layout: post
title: "Robust Fruit Counting: Combining Deep Learning, Tracking, and Structure from Motion"
date: 2018-04-01 15:44:58
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking CNN Deep_Learning Detection
author: Xu Liu, Steven W. Chen, Shreyas Aditya, Nivedha Sivakumar, Sandeep Dcunha, Chao Qu, Camillo J. Taylor, Jnaneshwar Das, Vijay Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel fruit counting pipeline that combines deep segmentation, frame to frame tracking, and 3D localization to accurately count visible fruits across a sequence of images. Our pipeline works on image streams from a monocular camera, both in natural light, as well as with controlled illumination at night. We first train a Fully Convolutional Network (FCN) and segment video frame images into fruit and non-fruit pixels. We then track fruits across frames using the Hungarian Algorithm where the objective cost is determined from a Kalman Filter corrected Kanade-Lucas-Tomasi (KLT) Tracker. In order to correct the estimated count from tracking process, we combine tracking results with a Structure from Motion (SfM) algorithm to calculate relative 3D locations and size estimates to reject outliers and double counted fruit tracks. We evaluate our algorithm by comparing with ground-truth human-annotated visual counts. Our results demonstrate that our pipeline is able to accurately and reliably count fruits across image sequences, and the correction step can significantly improve the counting accuracy and robustness. Although discussed in the context of fruit counting, our work can extend to detection, tracking, and counting of a variety of other stationary features of interest such as leaf-spots, wilt, and blossom.

##### Abstract (translated by Google)
我们提出了一种新颖的水果计数管道，它将深度分割，帧到帧跟踪以及3D定位结合起来，以准确地对一系列图像中的可见水果进行计数。我们的流水线适用于单筒照相机的图像流，无论是在自然光下，还是在夜间都可控照明。我们首先训练一个完全卷积网络（FCN），并将视频帧图像分割成水果和非水果像素。然后，我们使用匈牙利算法在各帧之间追踪水果，其中客观成本由卡尔曼滤波器校正的Kanade-Lucas-Tomasi（KLT）追踪器确定。为了纠正跟踪过程中估计的计数，我们将跟踪结果与运动结构（SfM）算法相结合，计算相对3D位置和尺寸估计值，以拒绝异常值和双重计数果实轨迹。我们通过与地面实况人类注释视觉计数进行比较来评估我们的算法。我们的结果表明，我们的流水线能够准确可靠地对图像序列中的水果进行计数，校正步骤可以显着提高计数精度和鲁棒性。尽管在果实计数方面进行了讨论，但我们的工作可以扩展到检测，跟踪和计算各种其他固定的感兴趣特征，如叶斑病，枯萎病和开花。

##### URL
[http://arxiv.org/abs/1804.00307](http://arxiv.org/abs/1804.00307)

##### PDF
[http://arxiv.org/pdf/1804.00307](http://arxiv.org/pdf/1804.00307)

