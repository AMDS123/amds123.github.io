---
layout: post
title: "Object Detection in Videos with Tubelet Proposal Networks"
date: 2017-04-10 08:39:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection RNN Detection
author: Kai Kang, Hongsheng Li, Tong Xiao, Wanli Ouyang, Junjie Yan, Xihui Liu, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection in videos has drawn increasing attention recently with the introduction of the large-scale ImageNet VID dataset. Different from object detection in static images, temporal information in videos is vital for object detection. To fully utilize temporal information, state-of-the-art methods are based on spatiotemporal tubelets, which are essentially sequences of associated bounding boxes across time. However, the existing methods have major limitations in generating tubelets in terms of quality and efficiency. Motion-based methods are able to obtain dense tubelets efficiently, but the lengths are generally only several frames, which is not optimal for incorporating long-term temporal information. Appearance-based methods, usually involving generic object tracking, could generate long tubelets, but are usually computationally expensive. In this work, we propose a framework for object detection in videos, which consists of a novel tubelet proposal network to efficiently generate spatiotemporal proposals, and a Long Short-term Memory (LSTM) network that incorporates temporal information from tubelet proposals for achieving high object detection accuracy in videos. Experiments on the large-scale ImageNet VID dataset demonstrate the effectiveness of the proposed framework for object detection in videos.

##### Abstract (translated by Google)
最近随着大规模ImageNet VID数据集的引入，视频中的对象检测越来越受到关注。与静态图像中的物体检测不同，视频中的时间信息对于物体检测至关重要。为了充分利用时间信息，最先进的方法基于时空小管，其基本上是随着时间的关联边界框的序列。然而，现有的方法在质量和效率方面产生小管方面有很大的局限性。基于运动的方法能够有效地获得密集的小管，但是长度通常只有几个帧，这对于并入长期的时间信息并不是最佳的。通常涉及通用对象跟踪的基于外观的方法可以产生长的小管，但是通常在计算上是昂贵的。在这项工作中，我们提出了一个视频中的对象检测框架，它包括一个新颖的小管建议网络，有效地产生时空提议，以及一个长期短期记忆（LSTM）网络，包含来自小管建议的时间信息以实现高对象视频中的检测精度。在大规模的ImageNet VID数据集上的实验证明了所提出的视频中的对象检测框架的有效性。

##### URL
[https://arxiv.org/abs/1702.06355](https://arxiv.org/abs/1702.06355)

