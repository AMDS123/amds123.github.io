---
layout: post
title: "ME R-CNN: Multi-Expert R-CNN for Object Detection"
date: 2017-12-01 15:13:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Hyungtae Lee, Sungmin Eum, Heesung Kwon
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Multi-Expert Region-based CNN (ME R-CNN) which is equipped with multiple experts and built on top of the R-CNN framework known to be one of the state-of-the-art object detection methods. ME R-CNN focuses in better capturing the appearance variations caused by different shapes, poses, and viewing angles. The proposed approach consists of three experts each responsible for objects with particular shapes: horizontally elongated, square-like, and vertically elongated. On top of using selective search which provides a compact, yet effective set of region of interests (RoIs) for object detection, we augmented the set by also employing the exhaustive search for training only. Incorporating the exhaustive search can provide complementary advantages: i) it captures the multitude of neighboring RoIs missed by the selective search, and thus ii) provide significantly larger amount of training examples. We show that the ME R-CNN architecture provides considerable performance increase over the baselines on PASCAL VOC 07, 12, and MS COCO datasets.

##### Abstract (translated by Google)
我们引入了多专家型CNN（ME R-CNN），该系统配备了多位专家，并基于R-CNN框架构建而成，该架构被称为最先进的对象检测方法之一。 ME R-CNN专注于更好地捕捉由不同形状，姿势和视角引起的外观变化。所提出的方法由三位专家组成，每位专家负责具有特定形状的物体：水平伸长，方形和垂直伸长。除了使用选择性搜索提供了一个紧凑而有效的目标检测区域（RoIs）之外，我们还通过仅使用穷尽搜索来扩充了该集合。结合穷举搜索可以提供相辅相成的优势：i）捕获选择性搜索所遗漏的多个相邻RoI，从而ii）提供显着更多的训练实例。我们显示ME R-CNN架构提供了相对于PASCAL VOC 07,12和MS COCO数据集上的基线的相当大的性能增加。

##### URL
[https://arxiv.org/abs/1704.01069](https://arxiv.org/abs/1704.01069)

