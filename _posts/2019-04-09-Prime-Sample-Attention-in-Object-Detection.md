---
layout: post
title: "Prime Sample Attention in Object Detection"
date: 2019-04-09 17:59:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Detection
author: Yuhang Cao, Kai Chen, Chen Change Loy, Dahua Lin
mathjax: true
---

* content
{:toc}

##### Abstract
It is a common paradigm in object detection frameworks to treat all samples equally and target at maximizing the performance on average. In this work, we revisit this paradigm through a careful study on how different samples contribute to the overall performance measured in terms of mAP. Our study suggests that the samples in each mini-batch are neither independent nor equally important, and therefore a better classifier on average does not necessarily mean higher mAP. Motivated by this study, we propose the notion of Prime Samples, those that play a key role in driving the detection performance. We further develop a simple yet effective sampling and learning strategy called PrIme Sample Attention (PISA) that directs the focus of the training process towards such samples. Our experiments demonstrate that it is often more effective to focus on prime samples than hard samples when training a detector. Particularly, On the MSCOCO dataset, PISA outperforms the random sampling baseline and hard mining schemes, e.g. OHEM and Focal Loss, consistently by more than 1% on both single-stage and two-stage detectors, with a strong backbone ResNeXt-101.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04821](http://arxiv.org/abs/1904.04821)

##### PDF
[http://arxiv.org/pdf/1904.04821](http://arxiv.org/pdf/1904.04821)

