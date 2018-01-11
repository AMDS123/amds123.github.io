---
layout: post
title: "Focus: Querying Large Video Datasets with Low Latency and Low Cost"
date: 2018-01-10 18:52:25
categories: arXiv_CV
tags: arXiv_CV CNN
author: Kevin Hsieh, Ganesh Ananthanarayanan, Peter Bodik, Paramvir Bahl, Matthai Philipose, Phillip B. Gibbons, Onur Mutlu
mathjax: true
---

* content
{:toc}

##### Abstract
Large volumes of videos are continuously recorded from cameras deployed for traffic control and surveillance with the goal of answering "after the fact" queries: identify video frames with objects of certain classes (cars, bags) from many days of recorded video. While advancements in convolutional neural networks (CNNs) have enabled answering such queries with high accuracy, they are too expensive and slow. We build Focus, a system for low-latency and low-cost querying on large video datasets. Focus uses cheap ingestion techniques to index the videos by the objects occurring in them. At ingest-time, it uses compression and video-specific specialization of CNNs. Focus handles the lower accuracy of the cheap CNNs by judiciously leveraging expensive CNNs at query-time. To reduce query time latency, we cluster similar objects and hence avoid redundant processing. Using experiments on video streams from traffic, surveillance and news channels, we see that Focus uses 58X fewer GPU cycles than running expensive ingest processors and is 37X faster than processing all the video at query time.

##### Abstract (translated by Google)
为了进行“事后”查询，部署的交通控制和监视摄像机连续记录大量视频：从录制视频的多天内，用特定类别的对象（汽车，行李）识别视频帧。虽然卷积神经网络（CNN）的进步使得能够高精度地回答这样的查询，但是它们太昂贵且缓慢。我们构建了Focus，这是一个针对大型视频数据集的低延迟和低成本查询系统。焦点使用便宜的摄取技术来对视频中的对象进行索引。在摄取时间，它使用压缩和视频特定的CNN专业化。焦点通过在查询时巧妙地利用昂贵的CNN来处理低成本CNN的低精度。为了减少查询时间延迟，我们将类似的对象聚类，从而避免冗余处理。通过对来自交通，监控和新闻频道的视频流的实验，我们看到Focus的运行速度比运行昂贵的摄像处理器少58倍，比查询时间处理所有视频要快37倍。

##### URL
[https://arxiv.org/abs/1801.03493](https://arxiv.org/abs/1801.03493)

##### PDF
[https://arxiv.org/pdf/1801.03493](https://arxiv.org/pdf/1801.03493)

