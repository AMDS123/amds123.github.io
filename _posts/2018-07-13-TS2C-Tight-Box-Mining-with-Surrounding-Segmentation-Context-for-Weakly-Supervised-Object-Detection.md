---
layout: post
title: "TS2C: Tight Box Mining with Surrounding Segmentation Context for Weakly Supervised Object Detection"
date: 2018-07-13 03:38:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Weakly_Supervised Detection
author: Yunchao Wei, Zhiqiang Shen, Bowen Cheng, Honghui Shi, Jinjun Xiong, Jiashi Feng, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
This work provides a simple approach to discover tight object bounding boxes with only image-level supervision, called Tight box mining with Surrounding Segmentation Context (TS2C). We observe that object candidates mined through current multiple instance learning methods are usually trapped to discriminative object parts, rather than the entire object. TS2C leverages surrounding segmentation context derived from weakly-supervised segmentation to suppress such low-quality distracting candidates and boost the high-quality ones. Specifically, TS2C is developed based on two key properties of desirable bounding boxes: 1) high purity, meaning most pixels in the box are with high object response, and 2) high completeness, meaning the box covers high object response pixels comprehensively. With such novel and computable criteria, more tight candidates can be discovered for learning a better object detector. With TS2C, we obtain 48.0% and 44.4% mAP scores on VOC 2007 and 2012 benchmarks, which are the new state-of-the-arts.

##### Abstract (translated by Google)
这项工作提供了一种简单的方法来发现紧密的对象边界框，只有图像级监督，称为紧密框挖掘与周围分割上下文（TS2C）。我们观察到通过当前多实例学习方法挖掘的对象候选者通常被捕获到判别对象部分，而不是整个对象。 TS2C利用从弱监督分割得到的周围分割上下文来抑制这种低质量的分散候选者并提升高质量的候选者。具体而言，TS2C基于期望的边界框的两个关键属性而开发：1）高纯度，意味着框中的大多数像素具有高对象响应，以及2）高完整性，意味着框全面地覆盖高对象响应像素。利用这种新颖且可计算的标准，可以发现更紧密的候选者来学习更好的物体检测器。通过TS2C，我们在VOC 2007和2012年基准测试中获得了48.0％和44.4％的mAP分数，这是最新的技术水平。

##### URL
[http://arxiv.org/abs/1807.04897](http://arxiv.org/abs/1807.04897)

##### PDF
[http://arxiv.org/pdf/1807.04897](http://arxiv.org/pdf/1807.04897)

