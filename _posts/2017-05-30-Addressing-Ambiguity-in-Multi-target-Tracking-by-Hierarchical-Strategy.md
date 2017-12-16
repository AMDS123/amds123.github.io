---
layout: post
title: "Addressing Ambiguity in Multi-target Tracking by Hierarchical Strategy"
date: 2017-05-30 16:11:34
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection
author: Ali Taalimi, Liu Liu, Hairong Qi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel hierarchical approach for the simultaneous tracking of multiple targets in a video. We use a network flow approach to link detections in low-level and tracklets in high-level. At each step of the hierarchy, the confidence of candidates is measured by using a new scoring system, ConfRank, that considers the quality and the quantity of its neighborhood. The output of the first stage is a collection of safe tracklets and unlinked high-confidence detections. For each individual detection, we determine if it belongs to an existing or is a new tracklet. We show the effect of our framework to recover missed detections and reduce switch identity. The proposed tracker is referred to as TVOD for multi-target tracking using the visual tracker and generic object detector. We achieve competitive results with lower identity switches on several datasets comparing to state-of-the-art.

##### Abstract (translated by Google)
本文提出了一种新的分层方法，用于同时跟踪视频中的多个目标。我们使用网络流量方法来连接高层次的检测和低层次的检测。在层次结构的每一步，候选人的信心是通过使用一个新的评分系统，ConfRank来衡量的，该系统考虑了邻居的质量和数量。第一阶段的输出是安全的tracklets和非链接的高可信度检测的集合。对于每个单独的检测，我们确定它是属于现有的还是新的tracklet。我们展示了我们的框架来恢复漏检和减少交换机身份的影响。所提出的跟踪器被称为TVOD，用于使用视觉跟踪器和通用对象检测器的多目标跟踪。与最先进的技术相比，我们在几个数据集上使用较低的身份切换来获得竞争性的结果。

##### URL
[https://arxiv.org/abs/1705.10716](https://arxiv.org/abs/1705.10716)

##### PDF
[https://arxiv.org/pdf/1705.10716](https://arxiv.org/pdf/1705.10716)

