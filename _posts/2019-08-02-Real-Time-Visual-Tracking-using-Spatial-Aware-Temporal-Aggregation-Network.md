---
layout: post
title: "Real Time Visual Tracking using Spatial-Aware Temporal Aggregation Network"
date: 2019-08-02 03:22:58
categories: arXiv_CV
tags: arXiv_CV Tracking Relation
author: Tao Hu, Lichao Huang, Xianming Liu, Han Shen
mathjax: true
---

* content
{:toc}

##### Abstract
More powerful feature representations derived from deep neural networks benefit visual tracking algorithms widely. However, the lack of exploitation on temporal information prevents tracking algorithms from adapting to appearances changing or resisting to drift. This paper proposes a correlation filter based tracking method which aggregates historical features in a spatial-aligned and scale-aware paradigm. The features of historical frames are sampled and aggregated to search frame according to a pixel-level alignment module based on deformable convolutions. In addition, we also use a feature pyramid structure to handle motion estimation at different scales, and address the different demands on feature granularity between tracking losses and deformation offset learning. By this design, the tracker, named as Spatial-Aware Temporal Aggregation network (SATA), is able to assemble appearances and motion contexts of various scales in a time period, resulting in better performance compared to a single static image. Our tracker achieves leading performance in OTB2013, OTB2015, VOT2015, VOT2016 and LaSOT, and operates at a real-time speed of 26 FPS, which indicates our method is effective and practical. Our code will be made publicly available at \href{https://github.com/ecart18/SATA}{https://github.com/ecart18/SATA}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00692](http://arxiv.org/abs/1908.00692)

##### PDF
[http://arxiv.org/pdf/1908.00692](http://arxiv.org/pdf/1908.00692)

