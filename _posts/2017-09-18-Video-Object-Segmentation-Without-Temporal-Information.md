---
layout: post
title: "Video Object Segmentation Without Temporal Information"
date: 2017-09-18 16:28:02
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Kevis-Kokitsi Maninis, Sergi Caelles, Yuhua Chen, Jordi Pont-Tuset, Laura Leal-Taixé, Daniel Cremers, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Video Object Segmentation, and video processing in general, has been historically dominated by methods that rely on the temporal consistency and redundancy in consecutive video frames. When the temporal smoothness is suddenly broken, such as when an object is occluded, or some frames are missing in a sequence, the result of these methods can deteriorate significantly or they may not even produce any result at all. This paper explores the orthogonal approach of processing each frame independently, i.e disregarding the temporal information. In particular, it tackles the task of semi-supervised video object segmentation: the separation of an object from the background in a video, given its mask in the first frame. We present Semantic One-Shot Video Object Segmentation (OSVOS-S), based on a fully-convolutional neural network architecture that is able to successively transfer generic semantic information, learned on ImageNet, to the task of foreground segmentation, and finally to learning the appearance of a single annotated object of the test sequence (hence one shot). We show that instance level semantic information, when combined effectively, can dramatically improve the results of our previous method, OSVOS. We perform experiments on two recent video segmentation databases, which show that OSVOS-S is both the fastest and most accurate method in the state of the art.

##### Abstract (translated by Google)
一般而言，视频对象分割和视频处理历来被依赖于连续视频帧中的时间一致性和冗余度的方法所主导。当时间平滑度突然中断，比如当一个对象被遮挡，或者一些帧在一个序列中缺失时，这些方法的结果可能会显着恶化，甚至根本不会产生任何结果。本文探讨了独立处理每一帧的正交方法，即不考虑时间信息。特别是，它解决了半监督视频对象分割的任务：在视频中将对象从背景中分离出来，给定其在第一帧中的掩码。基于全卷积神经网络体系结构，我们提出了语义一次性视频对象分割（OSVOS-S），它能够将在ImageNet上学习的通用语义信息连续地转移到前景分割任务，最后学习测试序列的单个注释对象的外观（因此是一个镜头）。我们展示了实例级别的语义信息，当有效地结合时，可以显着改善我们以前的方法OSVOS的结果。我们在两个最近的视频分割数据库上进行了实验，结果表明OSVOS-S是现有技术中最快和最准确的方法。

##### URL
[https://arxiv.org/abs/1709.06031](https://arxiv.org/abs/1709.06031)

##### PDF
[https://arxiv.org/pdf/1709.06031](https://arxiv.org/pdf/1709.06031)

