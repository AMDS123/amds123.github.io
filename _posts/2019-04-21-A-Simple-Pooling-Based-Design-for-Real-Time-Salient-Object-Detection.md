---
layout: post
title: "A Simple Pooling-Based Design for Real-Time Salient Object Detection"
date: 2019-04-21 09:22:25
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection CNN Detection
author: Jiang-Jiang Liu, Qibin Hou, Ming-Ming Cheng, Jiashi Feng, Jianmin Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
We solve the problem of salient object detection by investigating how to expand the role of pooling in convolutional neural networks. Based on the U-shape architecture, we first build a global guidance module (GGM) upon the bottom-up pathway, aiming at providing layers at different feature levels the location information of potential salient objects. We further design a feature aggregation module (FAM) to make the coarse-level semantic information well fused with the fine-level features from the top-down pathway. By adding FAMs after the fusion operations in the top-down pathway, coarse-level features from the GGM can be seamlessly merged with features at various scales. These two pooling-based modules allow the high-level semantic features to be progressively refined, yielding detail enriched saliency maps. Experiment results show that our proposed approach can more accurately locate the salient objects with sharpened details and hence substantially improve the performance compared to the previous state-of-the-arts. Our approach is fast as well and can run at a speed of more than 30 FPS when processing a $300 \times 400$ image. Code can be found at <a href="http://mmcheng.net/poolnet/.">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09569](http://arxiv.org/abs/1904.09569)

##### PDF
[http://arxiv.org/pdf/1904.09569](http://arxiv.org/pdf/1904.09569)

