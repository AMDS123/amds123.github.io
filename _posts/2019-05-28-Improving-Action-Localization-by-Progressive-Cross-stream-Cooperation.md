---
layout: post
title: "Improving Action Localization by Progressive Cross-stream Cooperation"
date: 2019-05-28 02:29:12
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Classification Detection
author: Rui Su, Wanli Ouyang, Luping Zhou, Dong Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Spatio-temporal action localization consists of three levels of tasks: spatial localization, action classification, and temporal segmentation. In this work, we propose a new Progressive Cross-stream Cooperation (PCSC) framework to use both region proposals and features from one stream (i.e. Flow/RGB) to help another stream (i.e. RGB/Flow) to iteratively improve action localization results and generate better bounding boxes in an iterative fashion. Specifically, we first generate a larger set of region proposals by combining the latest region proposals from both streams, from which we can readily obtain a larger set of labelled training samples to help learn better action detection models. Second, we also propose a new message passing approach to pass information from one stream to another stream in order to learn better representations, which also leads to better action detection models. As a result, our iterative framework progressively improves action localization results at the frame level. To improve action localization results at the video level, we additionally propose a new strategy to train class-specific actionness detectors for better temporal segmentation, which can be readily learnt by focusing on "confusing" samples from the same action class. Comprehensive experiments on two benchmark datasets UCF-101-24 and J-HMDB demonstrate the effectiveness of our newly proposed approaches for spatio-temporal action localization in realistic scenarios.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11575](https://arxiv.org/abs/1905.11575)

##### PDF
[https://arxiv.org/pdf/1905.11575](https://arxiv.org/pdf/1905.11575)

