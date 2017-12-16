---
layout: post
title: "Extreme clicking for efficient object annotation"
date: 2017-08-09 08:05:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Detection
author: Dim P. Papadopoulos, Jasper R. R. Uijlings, Frank Keller, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
Manually annotating object bounding boxes is central to building computer vision datasets, and it is very time consuming (annotating ILSVRC [53] took 35s for one high-quality box [62]). It involves clicking on imaginary corners of a tight box around the object. This is difficult as these corners are often outside the actual object and several adjustments are required to obtain a tight box. We propose extreme clicking instead: we ask the annotator to click on four physical points on the object: the top, bottom, left- and right-most points. This task is more natural and these points are easy to find. We crowd-source extreme point annotations for PASCAL VOC 2007 and 2012 and show that (1) annotation time is only 7s per box, 5x faster than the traditional way of drawing boxes [62]; (2) the quality of the boxes is as good as the original ground-truth drawn the traditional way; (3) detectors trained on our annotations are as accurate as those trained on the original ground-truth. Moreover, our extreme clicking strategy not only yields box coordinates, but also four accurate boundary points. We show (4) how to incorporate them into GrabCut to obtain more accurate segmentations than those delivered when initializing it from bounding boxes; (5) semantic segmentations models trained on these segmentations outperform those trained on segmentations derived from bounding boxes.

##### Abstract (translated by Google)
手动注释对象边界框是构建计算机视觉数据集的核心，而且非常耗时（注释ILSVRC [53]花了35s来处理一个高质量的盒子[62]）。它包括点击围绕对象的紧框的虚角。这是困难的，因为这些角落通常在实际物体之外，需要进行几次调整以获得紧密的盒子。我们建议使用极端点击：我们要求注释者点击对象上的四个物理点：顶部，底部，左侧和右侧的点。这个任务更自然，这些点很容易找到。我们对PASCAL VOC 2007和2012的极端点注释进行分组，并且显示（1）注释时间仅为每盒7s，比传统绘图盒的速度快5倍[62]。 （2）箱子的质量和原来的传统方式一样好， （3）在我们的注释上训练的探测器与那些在原始地面真相上训练的探测器一样准确。而且，我们的极端点击策略不仅可以得到箱子的坐标，还可以得到四个精确的边界点。我们展示（4）如何将它们合并到GrabCut中，以获得比从边界框初始化时更精确的分割; （5）在这些分割上训练的语义分割模型胜过那些在从边界框派生的分割上训练的模型。

##### URL
[https://arxiv.org/abs/1708.02750](https://arxiv.org/abs/1708.02750)

##### PDF
[https://arxiv.org/pdf/1708.02750](https://arxiv.org/pdf/1708.02750)

