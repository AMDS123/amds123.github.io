---
layout: post
title: "G-CNN: an Iterative Grid Based Object Detector"
date: 2016-04-25 20:40:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Mahyar Najibi, Mohammad Rastegari, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce G-CNN, an object detection technique based on CNNs which works without proposal algorithms. G-CNN starts with a multi-scale grid of fixed bounding boxes. We train a regressor to move and scale elements of the grid towards objects iteratively. G-CNN models the problem of object detection as finding a path from a fixed grid to boxes tightly surrounding the objects. G-CNN with around 180 boxes in a multi-scale grid performs comparably to Fast R-CNN which uses around 2K bounding boxes generated with a proposal technique. This strategy makes detection faster by removing the object proposal stage as well as reducing the number of boxes to be processed.

##### Abstract (translated by Google)
我们引入G-CNN，一种基于CNN的对象检测技术，不需要提议算法。 G-CNN从一个固定包围盒的多尺度网格开始。我们训练一个回归器来迭代地移动和缩放网格的元素。 G-CNN将对象检测的问题模拟为从固定网格到紧密围绕对象的盒子的路径。在多尺度网格中有大约180个盒子的G-CNN与使用提议技术产生的约2K包围盒子的快速R-CNN相当。该策略通过删除对象提议阶段以及减少要处理的框的数量来使得检测更快。

##### URL
[https://arxiv.org/abs/1512.07729](https://arxiv.org/abs/1512.07729)

##### PDF
[https://arxiv.org/pdf/1512.07729](https://arxiv.org/pdf/1512.07729)

