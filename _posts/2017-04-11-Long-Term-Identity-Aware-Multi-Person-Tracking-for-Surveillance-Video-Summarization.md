---
layout: post
title: "Long-Term Identity-Aware Multi-Person Tracking for Surveillance Video Summarization"
date: 2017-04-11 01:21:20
categories: arXiv_CV
tags: arXiv_CV Face Summarization Tracking Detection Recognition Face_Recognition
author: Shoou-I Yu, Yi Yang, Xuanchong Li, Alexander G. Hauptmann
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-person tracking plays a critical role in the analysis of surveillance video. However, most existing work focus on shorter-term (e.g. minute-long or hour-long) video sequences. Therefore, we propose a multi-person tracking algorithm for very long-term (e.g. month-long) multi-camera surveillance scenarios. Long-term tracking is challenging because 1) the apparel/appearance of the same person will vary greatly over multiple days and 2) a person will leave and re-enter the scene numerous times. To tackle these challenges, we leverage face recognition information, which is robust to apparel change, to automatically reinitialize our tracker over multiple days of recordings. Unfortunately, recognized faces are unavailable oftentimes. Therefore, our tracker propagates identity information to frames without recognized faces by uncovering the appearance and spatial manifold formed by person detections. We tested our algorithm on a 23-day 15-camera data set (4,935 hours total), and we were able to localize a person 53.2% of the time with 69.8% precision. We further performed video summarization experiments based on our tracking output. Results on 116.25 hours of video showed that we were able to generate a reasonable visual diary (i.e. a summary of what a person did) for different people, thus potentially opening the door to automatic summarization of the vast amount of surveillance video generated every day.

##### Abstract (translated by Google)
多人追踪在监控视频分析中起着至关重要的作用。然而，大多数现有的工作集中于短期（例如，分钟或长达一小时）的视频序列。因此，我们提出了一种用于非常长期（例如，一个月）的多摄像机监视场景的多人跟踪算法。长期跟踪是具有挑战性的，因为1）同一人的服装/外观将在多天内差异很大，并且2）一个人将多次离开并重新进入现场。为了应对这些挑战，我们利用面部识别信息，这对于服装的变化是强大的，可以在多天的记录中自动重新初始化我们的追踪器。不幸的是，经常识别的面孔不可用。因此，我们的跟踪器通过揭示人物检测形成的外观和空间流形，将身份信息传播到没有识别人脸的框架。我们在一个23天的15-相机数据集（总共4935小时）上测试了我们的算法，并且我们能够以69.8％的精度将53.2％的时间本地化。我们进一步根据我们的跟踪输出进行视频总结实验。在116.25小时的视频结果显示，我们能够生成一个合理的视觉日记（即一个人做了什么摘要）为不同的人，从而可能打开自动总结每天产生的大量监控视频的大门。

##### URL
[https://arxiv.org/abs/1604.07468](https://arxiv.org/abs/1604.07468)

##### PDF
[https://arxiv.org/pdf/1604.07468](https://arxiv.org/pdf/1604.07468)

