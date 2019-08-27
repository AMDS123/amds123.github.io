---
layout: post
title: "SPGNet: Semantic Prediction Guidance for Scene Parsing"
date: 2019-08-26 16:58:12
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation Semantic_Segmentation Prediction
author: Bowen Cheng, Liang-Chieh Chen, Yunchao Wei, Yukun Zhu, Zilong Huang, Jinjun Xiong, Thomas Huang, Wen-Mei Hwu, Honghui Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-scale context module and single-stage encoder-decoder structure are commonly employed for semantic segmentation. The multi-scale context module refers to the operations to aggregate feature responses from a large spatial extent, while the single-stage encoder-decoder structure encodes the high-level semantic information in the encoder path and recovers the boundary information in the decoder path. In contrast, multi-stage encoder-decoder networks have been widely used in human pose estimation and show superior performance than their single-stage counterpart. However, few efforts have been attempted to bring this effective design to semantic segmentation. In this work, we propose a Semantic Prediction Guidance (SPG) module which learns to re-weight the local features through the guidance from pixel-wise semantic prediction. We find that by carefully re-weighting features across stages, a two-stage encoder-decoder network coupled with our proposed SPG module can significantly outperform its one-stage counterpart with similar parameters and computations. Finally, we report experimental results on the semantic segmentation benchmark Cityscapes, in which our SPGNet attains 81.1% on the test set using only 'fine' annotations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09798](http://arxiv.org/abs/1908.09798)

##### PDF
[http://arxiv.org/pdf/1908.09798](http://arxiv.org/pdf/1908.09798)

