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


##### URL
[https://arxiv.org/abs/1807.04897](https://arxiv.org/abs/1807.04897)

##### PDF
[https://arxiv.org/pdf/1807.04897](https://arxiv.org/pdf/1807.04897)

