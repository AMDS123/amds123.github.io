---
layout: post
title: "Geometry-Based Next Frame Prediction from Monocular Video"
date: 2017-06-12 21:52:06
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Reza Mahjourian, Martin Wicke, Anelia Angelova
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of next frame prediction from video input. A recurrent convolutional neural network is trained to predict depth from monocular video input, which, along with the current video image and the camera trajectory, can then be used to compute the next frame. Unlike prior next-frame prediction approaches, we take advantage of the scene geometry and use the predicted depth for generating the next frame prediction. Our approach can produce rich next frame predictions which include depth information attached to each pixel. Another novel aspect of our approach is that it predicts depth from a sequence of images (e.g. in a video), rather than from a single still image. We evaluate the proposed approach on the KITTI dataset, a standard dataset for benchmarking tasks relevant to autonomous driving. The proposed method produces results which are visually and numerically superior to existing methods that directly predict the next frame. We show that the accuracy of depth prediction improves as more prior frames are considered.

##### Abstract (translated by Google)
我们考虑从视频输入中预测下一帧的问题。训练递归卷积神经网络以预测单眼视频输入的深度，其随着当前视频图像和摄像机轨迹被用于计算下一帧。与先前的下一帧预测方法不同，我们利用场景几何并利用预测深度来生成下一帧预测。我们的方法可以产生丰富的下一帧预测，其中包括附加到每个像素的深度信息。我们的方法的另一个新颖的方面是，它从一系列图像（例如在视频中）而不是从单个静止图像预测深度。我们评估了KITTI数据集上提出的方法，KITTI数据集是与自主驾驶相关的基准测试任务的标准数据集。所提出的方法产生的结果在视觉和数值上优于现有的直接预测下一帧的方法。我们表明，深度预测的准确性随着更多前面的帧被考虑而提高。

##### URL
[https://arxiv.org/abs/1609.06377](https://arxiv.org/abs/1609.06377)

##### PDF
[https://arxiv.org/pdf/1609.06377](https://arxiv.org/pdf/1609.06377)

