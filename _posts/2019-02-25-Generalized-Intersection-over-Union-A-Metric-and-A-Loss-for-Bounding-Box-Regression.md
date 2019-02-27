---
layout: post
title: "Generalized Intersection over Union: A Metric and A Loss for Bounding Box Regression"
date: 2019-02-25 21:47:33
categories: arXiv_AI
tags: arXiv_AI Object_Detection Detection
author: Hamid Rezatofighi, Nathan Tsoi, JunYoung Gwak, Amir Sadeghian, Ian Reid, Silvio Savarese
mathjax: true
---

* content
{:toc}

##### Abstract
Intersection over Union (IoU) is the most popular evaluation metric used in the object detection benchmarks. However, there is a gap between optimizing the commonly used distance losses for regressing the parameters of a bounding box and maximizing this metric value. The optimal objective for a metric is the metric itself. In the case of axis-aligned 2D bounding boxes, it can be shown that $IoU$ can be directly used as a regression loss. However, $IoU$ has a plateau making it infeasible to optimize in the case of non-overlapping bounding boxes. In this paper, we address the weaknesses of $IoU$ by introducing a generalized version as both a new loss and a new metric. By incorporating this generalized $IoU$ ($GIoU$) as a loss into the state-of-the art object detection frameworks, we show a consistent improvement on their performance using both the standard, $IoU$ based, and new, $GIoU$ based, performance measures on popular object detection benchmarks such as PASCAL VOC and MS COCO.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09630](http://arxiv.org/abs/1902.09630)

##### PDF
[http://arxiv.org/pdf/1902.09630](http://arxiv.org/pdf/1902.09630)

