---
layout: post
title: "Fast Multiple Landmark Localisation Using a Patch-based Iterative Network"
date: 2018-06-18 23:51:02
categories: arXiv_CV
tags: arXiv_CV CNN Inference Classification Quantitative Relation
author: Yuanwei Li, Amir Alansary, Juan J. Cerrolaza, Bishesh Khanal, Matthew Sinclair, Jacqueline Matthew, Chandni Gupta, Caroline Knight, Bernhard Kainz, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new Patch-based Iterative Network (PIN) for fast and accurate landmark localisation in 3D medical volumes. PIN utilises a Convolutional Neural Network (CNN) to learn the spatial relationship between an image patch and anatomical landmark positions. During inference, patches are repeatedly passed to the CNN until the estimated landmark position converges to the true landmark location. PIN is computationally efficient since the inference stage only selectively samples a small number of patches in an iterative fashion rather than a dense sampling at every location in the volume. Our approach adopts a multi-task learning framework that combines regression and classification to improve localisation accuracy. We extend PIN to localise multiple landmarks by using principal component analysis, which models the global anatomical relationships between landmarks. We have evaluated PIN using 72 3D ultrasound images from fetal screening examinations. PIN achieves quantitatively an average landmark localisation error of 5.59mm and a runtime of 0.44s to predict 10 landmarks per volume. Qualitatively, anatomical 2D standard scan planes derived from the predicted landmark locations are visually similar to the clinical ground truth.

##### Abstract (translated by Google)
我们提出了一种新的基于补丁的迭代网络（PIN），可在3D医疗卷中快速准确地标记本地化。 PIN利用卷积神经网络（CNN）来了解图像片和解剖标志位之间的空间关系。在推断过程中，贴片会重复传递到CNN，直到估计的地标位置收敛到真正的地标位置。 PIN在计算上是有效的，因为推理阶段仅以迭代的方式选择性地采样少量斑块，而不是体积中每个位置的密集采样。我们的方法采用多任务学习框架，结合回归和分类来提高本地化的准确性。我们通过使用主要成分分析来扩展PIN以定位多个地标，该主成分分析模拟地标之间的全局解剖关系。我们使用来自胎儿筛查检查的72个3D超声图像评估了PIN。 PIN在数量上实现了5.59mm的平均地标定位误差和0.44s的运行时间以预测每个体积的10个地标。定性地，从预测的界标位置导出的解剖学2D标准扫描平面在视觉上与临床实际情况类似。

##### URL
[http://arxiv.org/abs/1806.06987](http://arxiv.org/abs/1806.06987)

##### PDF
[http://arxiv.org/pdf/1806.06987](http://arxiv.org/pdf/1806.06987)

