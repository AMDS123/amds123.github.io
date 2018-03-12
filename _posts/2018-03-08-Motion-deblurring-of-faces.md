---
layout: post
title: "Motion deblurring of faces"
date: 2018-03-08 23:07:22
categories: arXiv_CV
tags: arXiv_CV Face Tracking Optimization Recognition
author: Grigorios G. Chrysos, Paolo Favaro, Stefanos Zafeiriou
mathjax: true
---

* content
{:toc}

##### Abstract
Face analysis is a core part of computer vision, in which remarkable progress has been observed in the past decades. Current methods achieve recognition and tracking with invariance to fundamental modes of variation such as illumination, 3D pose, expressions. Notwithstanding, a much less standing mode of variation is motion deblurring, which however presents substantial challenges in face analysis. Recent approaches either make oversimplifying assumptions, e.g. in cases of joint optimization with other tasks, or fail to preserve the highly structured shape/identity information. Therefore, we propose a data-driven method that encourages identity preservation. The proposed model includes two parallel streams (sub-networks): the first deblurs the image, the second implicitly extracts and projects the identity of both the sharp and the blurred image in similar subspaces. We devise a method for creating realistic motion blur by averaging a variable number of frames to train our model. The averaged images originate from a 2MF2 dataset with 10 million facial frames, which we introduce for the task. Considering deblurring as an intermediate step, we utilize the deblurred outputs to conduct a thorough experimentation on high-level face analysis tasks, i.e. landmark localization and face verification. The experimental evaluation demonstrates the superiority of our method.

##### Abstract (translated by Google)
脸部分析是计算机视觉的核心部分，在过去的几十年里，人们观察到了显着的进步。目前的方法实现了对基本变化模式（例如照明，3D姿态，表达）的不变性的识别和跟踪。尽管如此，一种不太常见的变化模式是运动衰减，然而这在面部分析中提出了实质性的挑战。最近的方法要么做出过于简单化的假设，例如在与其他任务联合优化的情况下，或未能保留高度结构化的形状/身份信息。因此，我们提出了一种鼓励身份保护的数据驱动方法。所提出的模型包括两个并行的流（子网）：第一个去除图像，第二个隐含地提取和投影类似子空间中的锐化和模糊图像的身份。我们设计了一种通过平均可变数量的帧来训练我们的模型来创建逼真的运动模糊的方法。平均图像来源于一个2MF2数据集，其中包含1000万个面部框架，我们将介绍这些框架用于该任务。考虑到去模糊作为一个中间步骤，我们利用去模糊输出对高级别人脸分析任务（即地标定位和人脸验证）进行彻底的实验。实验评估证明了我们方法的优越性。

##### URL
[http://arxiv.org/abs/1803.03330](http://arxiv.org/abs/1803.03330)

##### PDF
[http://arxiv.org/pdf/1803.03330](http://arxiv.org/pdf/1803.03330)

