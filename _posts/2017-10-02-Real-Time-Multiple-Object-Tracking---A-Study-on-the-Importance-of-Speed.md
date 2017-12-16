---
layout: post
title: "Real-Time Multiple Object Tracking - A Study on the Importance of Speed"
date: 2017-10-02 16:26:37
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Detection
author: Samuel Murray
mathjax: true
---

* content
{:toc}

##### Abstract
In this project, we implement a multiple object tracker, following the tracking-by-detection paradigm, as an extension of an existing method. It works by modelling the movement of objects by solving the filtering problem, and associating detections with predicted new locations in new frames using the Hungarian algorithm. Three different similarity measures are used, which use the location and shape of the bounding boxes. Compared to other trackers on the MOTChallenge leaderboard, our method, referred to as C++SORT, is the fastest non-anonymous submission, while also achieving decent score on other metrics. By running our model on the Okutama-Action dataset, sampled at different frame-rates, we show that the performance is greatly reduced when running the model - including detecting objects - in real-time. In most metrics, the score is reduced by 50%, but in certain cases as much as 90%. We argue that this indicates that other, slower methods could not be used for tracking in real-time, but that more research is required specifically on this.

##### Abstract (translated by Google)
在这个项目中，我们实现了一个多目标跟踪器，跟踪检测模式，作为现有方法的扩展。它通过解决滤波问题对对象的运动进行建模，并使用匈牙利算法将检测与新帧中的预测新位置相关联。使用三种不同的相似性度量，它们使用边界框的位置和形状。与MOTChallenge排行榜上的其他跟踪器相比，我们的方法（称为C ++ SORT）是最快的非匿名提交，同时在其他指标上也取得了不错的评分。通过在Okutama-Action数据集上运行我们的模型，以不同的帧率进行采样，我们显示，实时运行模型（包括检测对象）时性能大大降低。在大多数指标中，得分降低了50％，但是在某些情况下，降幅高达90％。我们认为，这表明其他较慢的方法不能用于实时跟踪，但需要更多的研究。

##### URL
[https://arxiv.org/abs/1709.03572](https://arxiv.org/abs/1709.03572)

##### PDF
[https://arxiv.org/pdf/1709.03572](https://arxiv.org/pdf/1709.03572)

