---
layout: post
title: "Rotation-Sensitive Regression for Oriented Scene Text Detection"
date: 2018-03-14 13:29:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection
author: Minghui Liao, Zhen Zhu, Baoguang Shi, Gui-song Xia, Xiang Bai
mathjax: true
---

* content
{:toc}

##### Abstract
Text in natural images is of arbitrary orientations, requiring detection in terms of oriented bounding boxes. Normally, a multi-oriented text detector often involves two key tasks: 1) text presence detection, which is a classification problem disregarding text orientation; 2) oriented bounding box regression, which concerns about text orientation. Previous methods rely on shared features for both tasks, resulting in degraded performance due to the incompatibility of the two tasks. To address this issue, we propose to perform classification and regression on features of different characteristics, extracted by two network branches of different designs. Concretely, the regression branch extracts rotation-sensitive features by actively rotating the convolutional filters, while the classification branch extracts rotation-invariant features by pooling the rotation-sensitive features. The proposed method named Rotation-sensitive Regression Detector (RRD) achieves state-of-the-art performance on three oriented scene text benchmark datasets, including ICDAR 2015, MSRA-TD500, RCTW-17 and COCO-Text. Furthermore, RRD achieves a significant improvement on a ship collection dataset, demonstrating its generality on oriented object detection.

##### Abstract (translated by Google)
自然图像中的文本具有任意方向，需要根据定向边界框进行检测。通常情况下，多导向的文本检测器往往涉及两个关键任务：1）文本存在检测，这是一个无视文本方向的分类问题; 2）面向边界框的回归，它关注文本的方向。以前的方法依赖于这两个任务的共享功能，由于两个任务不兼容导致性能下降。为了解决这个问题，我们提出对不同设计的两个网络分支提取不同特征的特征进行分类和回归。具体而言，回归分支通过主动旋转卷积滤波器来提取旋转敏感特征，而分类分支通过汇集旋转敏感特征来提取旋转不变特征。所提出的方法名为旋转敏感回归检测器（RRD），在三个面向文本的基准数据集（包括ICDAR 2015，MSRA-TD500，RCTW-17和COCO-Text）上实现了最先进的性能。此外，RRD在船舶采集数据集上实现了重大改进，证明了其在面向对象检测方面的一般性。

##### URL
[https://arxiv.org/abs/1803.05265](https://arxiv.org/abs/1803.05265)

##### PDF
[https://arxiv.org/pdf/1803.05265](https://arxiv.org/pdf/1803.05265)

