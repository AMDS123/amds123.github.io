---
layout: post
title: "Supervision-by-Registration: An Unsupervised Approach to Improve the Precision of Facial Landmark Detectors"
date: 2018-07-03 03:52:45
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection
author: Xuanyi Dong, Shoou-I Yu, Xinshuo Weng, Shih-En Wei, Yi Yang, Yaser Sheikh
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present supervision-by-registration, an unsupervised approach to improve the precision of facial landmark detectors on both images and video. Our key observation is that the detections of the same landmark in adjacent frames should be coherent with registration, i.e., optical flow. Interestingly, the coherency of optical flow is a source of supervision that does not require manual labeling, and can be leveraged during detector training. For example, we can enforce in the training loss function that a detected landmark at frame$_{t-1}$ followed by optical flow tracking from frame$_{t-1}$ to frame$_t$ should coincide with the location of the detection at frame$_t$. Essentially, supervision-by-registration augments the training loss function with a registration loss, thus training the detector to have output that is not only close to the annotations in labeled images, but also consistent with registration on large amounts of unlabeled videos. End-to-end training with the registration loss is made possible by a differentiable Lucas-Kanade operation, which computes optical flow registration in the forward pass, and back-propagates gradients that encourage temporal coherency in the detector. The output of our method is a more precise image-based facial landmark detector, which can be applied to single images or video. With supervision-by-registration, we demonstrate (1) improvements in facial landmark detection on both images (300W, ALFW) and video (300VW, Youtube-Celebrities), and (2) significant reduction of jittering in video detections.

##### Abstract (translated by Google)
在本文中，我们提出了一种注册监督，一种无监督的方法来提高图像和视频上面部标志检测器的精度。我们的关键观察是相邻帧中相同地标的检测应该与配准（即光流）一致。有趣的是，光流的一致性是监督的来源，不需要手动标记，并且可以在探测器训练期间使用。例如，我们可以在训练损失函数中强制执行在帧$ _ {t-1} $处检测到的地标，然后从帧$ _ {t-1} $到帧$ _t $的光流跟踪应该与位置重合帧$ _t $的检测。基本上，通过登记监督增加了训练损失功能和注册损失，从而训练检测器使输出不仅接近标记图像中的注释，而且与大量未标记视频上的注册一致。通过可微分的Lucas-Kanade操作实现具有配准损失的端到端训练，该操作计算前向通道中的光流配准，并且反向传播促进检测器中的时间一致性的梯度。我们的方法的输出是更精确的基于图像的面部标志检测器，其可以应用于单个图像或视频。通过注册监督，我们证明了（1）在图像（300W，ALFW）和视频（300VW，Youtube-Celebrities）上的面部地标检测的改进，以及（2）视频检测中的抖动的显着减少。

##### URL
[https://arxiv.org/abs/1807.00966](https://arxiv.org/abs/1807.00966)

##### PDF
[https://arxiv.org/pdf/1807.00966](https://arxiv.org/pdf/1807.00966)

