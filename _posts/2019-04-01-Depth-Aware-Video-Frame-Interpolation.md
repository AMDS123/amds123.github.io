---
layout: post
title: "Depth-Aware Video Frame Interpolation"
date: 2019-04-01 13:19:59
categories: arXiv_CV
tags: arXiv_CV CNN Quantitative
author: Wenbo Bao, Wei-Sheng Lai, Chao Ma, Xiaoyun Zhang, Zhiyong Gao, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Video frame interpolation aims to synthesize nonexistent frames in-between the original frames. While significant advances have been made from the recent deep convolutional neural networks, the quality of interpolation is often reduced due to large object motion or occlusion. In this work, we propose a video frame interpolation method which explicitly detects the occlusion by exploring the depth information. Specifically, we develop a depth-aware flow projection layer to synthesize intermediate flows that preferably sample closer objects than farther ones. In addition, we learn hierarchical features to gather contextual information from neighboring pixels. The proposed model then warps the input frames, depth maps, and contextual features based on the optical flow and local interpolation kernels for synthesizing the output frame. Our model is compact, efficient, and fully differentiable. Quantitative and qualitative results demonstrate that the proposed model performs favorably against state-of-the-art frame interpolation methods on a wide variety of datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00830](http://arxiv.org/abs/1904.00830)

##### PDF
[http://arxiv.org/pdf/1904.00830](http://arxiv.org/pdf/1904.00830)

