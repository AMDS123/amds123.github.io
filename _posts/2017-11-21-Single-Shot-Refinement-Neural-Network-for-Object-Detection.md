---
layout: post
title: "Single-Shot Refinement Neural Network for Object Detection"
date: 2017-11-21 02:54:00
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Shifeng Zhang, Longyin Wen, Xiao Bian, Zhen Lei, Stan Z. Li
mathjax: true
---

* content
{:toc}

##### Abstract
For object detection, the two-stage approach (e.g., Faster R-CNN) has been achieving the highest accuracy, whereas the one-stage approach (e.g., SSD) has the advantage of high efficiency. To inherit the merits of both while overcoming their disadvantages, in this paper, we propose a novel single-shot based detector, called RefineDet, that achieves better accuracy than two-stage methods and maintains comparable efficiency of one-stage methods. RefineDet consists of two inter-connected modules, namely, the anchor refinement module and the object detection module. Specifically, the former aims to (1) filter out negative anchors to reduce search space for the classifier, and (2) coarsely adjust the locations and sizes of anchors to provide better initialization for the subsequent regressor. The latter module takes the refined anchors as the input from the former to further improve the regression and predict multi-class label. Meanwhile, we design a transfer connection block to transfer the features in the anchor refinement module to predict locations, sizes and class labels of objects in the object detection module. The multi-task loss function enables us to train the whole network in an end-to-end way. Extensive experiments on PASCAL VOC 2007, PASCAL VOC 2012, and MS COCO demonstrate that RefineDet achieves state-of-the-art detection accuracy with high efficiency. Code is available at this https URL .

##### Abstract (translated by Google)
对于对象检测，两阶段方法（例如更快的R-CNN）已达到最高精度，而一阶段方法（例如SSD）具有高效率的优点。为了继承两者的优点，克服它们的缺点，本文提出了一种称为RefineDet的新型单发检测器，比两阶段方法具有更好的准确性，并保持单阶段方法的效率。 RefineDet由两个相互连接的模块组成，即锚点优化模块和对象检测模块。具体而言，前者旨在（1）滤除负锚以减少分类器的搜索空间;（2）粗略地调整锚的位置和大小，以便为随后的回归器提供更好的初始化。后一模块将精化的锚点作为前者的输入，进一步改进回归和预测多类标签。同时，我们设计了一个转移连接块来转移锚点细化模块中的特征，以预测物体检测模块中物体的位置，大小和类别标签。多任务丢失功能使我们能够以一种端到端的方式来训练整个网络。在PASCAL VOC 2007，PASCAL VOC 2012和MS COCO上进行的大量实验表明，RefineDet能够高效地实现最先进的检测精度。代码可在此https网址获得。

##### URL
[https://arxiv.org/abs/1711.06897](https://arxiv.org/abs/1711.06897)

