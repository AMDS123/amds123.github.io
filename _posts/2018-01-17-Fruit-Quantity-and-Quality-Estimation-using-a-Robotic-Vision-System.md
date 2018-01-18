---
layout: post
title: "Fruit Quantity and Quality Estimation using a Robotic Vision System"
date: 2018-01-17 05:53:26
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: M. Halstead, C. McCool, S. Denman, T. Perez, C. Fookes
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate localisation of crop remains highly challenging in unstructured environments such as farms. Many of the developed systems still rely on the use of hand selected features for crop identification and often neglect the estimation of crop quantity and quality, which is key to assigning labor during farming processes. To alleviate these limitations we present a robotic vision system that can accurately estimate the quantity and quality of sweet pepper (Capsicum annuum L), a key horticultural crop. This system consists of three parts: detection, quality estimation, and tracking. Efficient detection is achieved using the FasterRCNN framework. Quality is then estimated in the same framework by learning a parallel layer which we show experimentally results in superior performance than treating quality as extra classes in the traditional Faster-RCNN framework. Evaluation of these two techniques outlines the improved performance of the parallel layer, where we achieve an F1 score of 77.3 for the parallel technique yet only 72.5 for the best scoring (red) of the multi-class implementation. To track the crop we present a tracking via detection approach, which uses the FasterRCNN with parallel layers, that is also a vision-only solution. This approach is cheap to implement as it only requires a camera and in experiments across 2 days we show that our proposed system can accurately estimate the number of sweet pepper present, within 4.1% of the ground truth.

##### Abstract (translated by Google)
农作物的非结构化环境对作物的精确定位依然非常具有挑战性。许多开发的系统仍然依赖手工选择特征进行作物鉴定，而往往忽视作物数量和质量的估算，这是农业生产过程中分配劳力的关键。为了减轻这些限制，我们提供了一个机器人视觉系统，可以准确地估计甜椒（辣椒辣椒），一个关键的园艺作物的数量和质量。该系统由三部分组成：检测，质量评估和跟踪。使用FasterRCNN框架可以实现有效的检测。然后通过学习一个平行层来评估质量，在平行层中，我们将实验结果表现为比传统Faster-RCNN框架中的额外类质量更好的性能。这两种技术的评估概述了并行层的改进性能，其中并行技术获得77.3的F1得分，而多级实现的最佳得分（红色）仅72.5。为了跟踪作物，我们提出了一种通过检测方法进行跟踪，该方法将FasterRCNN与平行层结合使用，这也是一种仅有视觉的解决方案。这种方法实施起来很便宜，因为它只需要一个摄像头，并且在两天的实验中我们表明，我们所提出的系统可以准确地估计存在的甜椒数量，在4.1％的基本事实中。

##### URL
[http://arxiv.org/abs/1801.05560](http://arxiv.org/abs/1801.05560)

##### PDF
[http://arxiv.org/pdf/1801.05560](http://arxiv.org/pdf/1801.05560)

