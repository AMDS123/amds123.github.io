---
layout: post
title: "Temporal Dynamic Graph LSTM for Action-driven Video Object Detection"
date: 2017-08-02 09:38:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge RNN Detection Relation Recognition
author: Yuan Yuan, Xiaodan Liang, Xiaolong Wang, Dit-Yan Yeung, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we investigate a weakly-supervised object detection framework. Most existing frameworks focus on using static images to learn object detectors. However, these detectors often fail to generalize to videos because of the existing domain shift. Therefore, we investigate learning these detectors directly from boring videos of daily activities. Instead of using bounding boxes, we explore the use of action descriptions as supervision since they are relatively easy to gather. A common issue, however, is that objects of interest that are not involved in human actions are often absent in global action descriptions known as "missing label". To tackle this problem, we propose a novel temporal dynamic graph Long Short-Term Memory network (TD-Graph LSTM). TD-Graph LSTM enables global temporal reasoning by constructing a dynamic graph that is based on temporal correlations of object proposals and spans the entire video. The missing label issue for each individual frame can thus be significantly alleviated by transferring knowledge across correlated objects proposals in the whole video. Extensive evaluations on a large-scale daily-life action dataset (i.e., Charades) demonstrates the superiority of our proposed method. We also release object bounding-box annotations for more than 5,000 frames in Charades. We believe this annotated data can also benefit other research on video-based object recognition in the future.

##### Abstract (translated by Google)
在本文中，我们研究了一个弱监督的对象检测框架。大多数现有的框架着重于使用静态图像来学习物体检测器。然而，由于现有的域名转换，这些检测器往往不能推广到视频。因此，我们直接从枯燥的日常活动视频中调查这些检测器。我们不使用边界框，而是使用行为描述作为监督，因为它们相对容易收集。然而，一个共同的问题是，不涉及人类行为的感兴趣的对象在被称为“缺失标签”的全球行为描述中经常不存在。为了解决这个问题，我们提出了一种新颖的时态动态图形Long Short Term Memory网络（TD-Graph LSTM）。 TD-Graph LSTM通过构建基于对象提议的时间相关性并横跨整个视频的动态图形来实现全局时间推理。因此，通过在整个视频中跨相关对象建议传递知识，可以显着缓解每个单独框架的缺失标签问题。对大规模的日常生活行为数据集（即Charades）的广泛评估证明了我们提出的方法的优越性。我们还在Charades中释放超过5,000帧的对象边界框注释。我们相信这个带注释的数据也可以有益于未来对视频对象识别的其他研究。

##### URL
[https://arxiv.org/abs/1708.00666](https://arxiv.org/abs/1708.00666)

##### PDF
[https://arxiv.org/pdf/1708.00666](https://arxiv.org/pdf/1708.00666)

