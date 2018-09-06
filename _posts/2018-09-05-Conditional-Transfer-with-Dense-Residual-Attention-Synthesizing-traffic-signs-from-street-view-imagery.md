---
layout: post
title: "Conditional Transfer with Dense Residual Attention: Synthesizing traffic signs from street-view imagery"
date: 2018-09-05 11:40:47
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Classification Detection
author: Clint Sebastian, Ries Uittenbogaard, Julien Vijverberg, Bas Boom, Peter H.N. de With
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection and classification of traffic signs in street-view imagery is an essential element for asset management, map making and autonomous driving. However, some traffic signs occur rarely and consequently, they are difficult to recognize automatically. To improve the detection and classification rates, we propose to generate images of traffic signs, which are then used to train a detector/classifier. In this research, we present an end-to-end framework that generates a realistic image of a traffic sign from a given image of a traffic sign and a pictogram of the target class. We propose a residual attention mechanism with dense concatenation called Dense Residual Attention, that preserves the background information while transferring the object information. We also propose to utilize multi-scale discriminators, so that the smaller scales of the output guide the higher resolution output. We have performed detection and classification tests across a large number of traffic sign classes, by training the detector using the combination of real and generated data. The newly trained model reduces the number of false positives by 1.2 - 1.5% at 99% recall in the detection tests and an absolute improvement of 4.65% (top-1 accuracy) in the classification tests.

##### Abstract (translated by Google)
街景图像中交通标志的目标检测和分类是资产管理，地图制作和自动驾驶的基本要素。然而，一些交通标志很少发生，因此很难自动识别。为了提高检测和分类率，我们建议生成交通标志的图像，然后用于训练检测器/分类器。在这项研究中，我们提出了一个端到端的框架，从交通标志的给定图像和目标类的象形图生成交通标志的真实图像。我们提出了一种称为Dense Residual Attention的密集级联的剩余注意机制，它在传输对象信息时保留背景信息。我们还建议使用多尺度鉴别器，以便输出的较小尺度引导更高分辨率的输出。我们通过使用实际数据和生成数据的组合训练检测器，对大量交通标志类别进行了检测和分类测试。新训练的模型在检测测试中，99％的召回率下，假阳性的数量减少了1.2-1.5％，在分类测试中绝对改善了4.65％（前1精度）。

##### URL
[http://arxiv.org/abs/1809.01444](http://arxiv.org/abs/1809.01444)

##### PDF
[http://arxiv.org/pdf/1809.01444](http://arxiv.org/pdf/1809.01444)

