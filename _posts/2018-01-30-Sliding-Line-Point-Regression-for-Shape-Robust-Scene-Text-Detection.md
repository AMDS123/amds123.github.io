---
layout: post
title: "Sliding Line Point Regression for Shape Robust Scene Text Detection"
date: 2018-01-30 12:58:10
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Yixing Zhu, Jun Du
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional text detection methods mostly focus on quadrangle text. In this study we propose a novel method named sliding line point regression (SLPR) in order to detect arbitrary-shape text in natural scene. SLPR regresses multiple points on the edge of text line and then utilizes these points to sketch the outlines of the text. The proposed SLPR can be adapted to many object detection architectures such as Faster R-CNN and R-FCN. Specifically, we first generate the smallest rectangular box including the text with region proposal network (RPN), then isometrically regress the points on the edge of text by using the vertically and horizontally sliding lines. To make full use of information and reduce redundancy, we calculate x-coordinate or y-coordinate of target point by the rectangular box position, and just regress the remaining y-coordinate or x-coordinate. Accordingly we can not only reduce the parameters of system, but also restrain the points which will generate more regular polygon. Our approach achieved competitive results on traditional ICDAR2015 Incidental Scene Text benchmark and curve text detection dataset CTW1500.

##### Abstract (translated by Google)
传统的文本检测方法主要集中在四边形文本上。在这项研究中，我们提出了一种新的滑动线点回归（SLPR）方法来检测自然场景中的任意形状的文本。 SLPR在文本行边缘回归多个点，然后利用这些点来勾画文本的轮廓。所提出的SLPR可以适应许多对象检测体系结构，例如更快的R-CNN和R-FCN。具体来说，我们首先生成包含区域提议网络（RPN）的文本的最小矩形框，然后利用垂直和水平滑动线等距地回归文本边缘上的点。为了充分利用信息并减少冗余，我们用矩形框的位置来计算目标点的x坐标或y坐标，然后回归剩余的y坐标或x坐标。因此，我们不仅可以减少系统的参数，而且可以限制产生更多正多边形的点。我们的方法在传统ICDAR2015附加场景文本基准和曲线文本检测数据集CTW1500上取得了有竞争力的结果。

##### URL
[http://arxiv.org/abs/1801.09969](http://arxiv.org/abs/1801.09969)

##### PDF
[http://arxiv.org/pdf/1801.09969](http://arxiv.org/pdf/1801.09969)

