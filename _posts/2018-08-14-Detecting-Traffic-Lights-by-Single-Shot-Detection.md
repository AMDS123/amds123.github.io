---
layout: post
title: "Detecting Traffic Lights by Single Shot Detection"
date: 2018-08-14 12:19:16
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Deep_Learning Detection
author: Julian M&#xfc;ller, Klaus Dietmayer
mathjax: true
---

* content
{:toc}

##### Abstract
Recent improvements in object detection are driven by the success of convolutional neural networks (CNN). They are able to learn rich features outperforming hand-crafted features. So far, research in traffic light detection mainly focused on hand-crafted features, such as color, shape or brightness of the traffic light bulb. This paper presents a deep learning approach for accurate traffic light detection in adapting a single shot detection (SSD) approach. SSD performs object proposals creation and classification using a single CNN. The original SSD struggles in detecting very small objects, which is essential for traffic light detection. By our adaptations it is possible to detect objects much smaller than ten pixels without increasing the input image size. We present an extensive evaluation on the DriveU Traffic Light Dataset (DTLD). We reach both, high accuracy and low false positive rates. The trained model is real-time capable with ten frames per second on a Nvidia Titan Xp. Code has been made available at https://github.com/julimueller/tl_ssd.

##### Abstract (translated by Google)
最近对物体检测的改进是由卷积神经网络（CNN）的成功驱动的。他们能够学习超越手工制作功能的丰富功能。到目前为止，交通灯检测的研究主要集中在手工制作的功能，如交通灯灯泡的颜色，形状或亮度。本文介绍了一种深度学习方法，用于在适应单次检测（SSD）方法中进行准确的交通灯检测。 SSD使用单个CNN执行对象建议创建和分类。最初的SSD在检测非常小的物体时很困难，这对于交通灯检测至关重要。通过我们的调整，可以检测远小于十个像素的物体而不增加输入图像尺寸。我们对DriveU Traffic Light Dataset（DTLD）进行了广泛的评估。我们同时达到了高精度和低误报率。经过训练的模型在Nvidia Titan Xp上具有每秒10帧的实时性。代码已在https://github.com/julimueller/tl_ssd上提供。

##### URL
[http://arxiv.org/abs/1805.02523](http://arxiv.org/abs/1805.02523)

##### PDF
[http://arxiv.org/pdf/1805.02523](http://arxiv.org/pdf/1805.02523)

