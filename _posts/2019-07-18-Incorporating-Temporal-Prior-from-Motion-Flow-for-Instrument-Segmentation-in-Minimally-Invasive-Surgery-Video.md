---
layout: post
title: "Incorporating Temporal Prior from Motion Flow for Instrument Segmentation in Minimally Invasive Surgery Video"
date: 2019-07-18 06:51:05
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention
author: Yueming Jin, Keyun Cheng, Qi Dou, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic instrument segmentation in video is an essentially fundamental yet challenging problem for robot-assisted minimally invasive surgery. In this paper, we propose a novel framework to leverage instrument motion information, by incorporating a derived temporal prior to an attention pyramid network for accurate segmentation. Our inferred prior can provide reliable indication of the instrument location and shape, which is propagated from the previous frame to the current frame according to inter-frame motion flow. This prior is injected to the middle of an encoder-decoder segmentation network as an initialization of a pyramid of attention modules, to explicitly guide segmentation output from coarse to fine. In this way, the temporal dynamics and the attention network can effectively complement and benefit each other. As additional usage, our temporal prior enables semi-supervised learning with periodically unlabeled video frames, simply by reverse execution. We extensively validate our method on the public 2017 MICCAI EndoVis Robotic Instrument Segmentation Challenge dataset with three different tasks. Our method consistently exceeds the state-of-the-art results across all three tasks by a large margin. Our semi-supervised variant also demonstrates a promising potential for reducing annotation cost in the clinical practice.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07899](http://arxiv.org/abs/1907.07899)

##### PDF
[http://arxiv.org/pdf/1907.07899](http://arxiv.org/pdf/1907.07899)

