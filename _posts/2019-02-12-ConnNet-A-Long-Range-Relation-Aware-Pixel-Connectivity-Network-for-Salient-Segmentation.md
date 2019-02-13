---
layout: post
title: "ConnNet: A Long-Range Relation-Aware Pixel-Connectivity Network for Salient Segmentation"
date: 2019-02-12 11:35:27
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Attention Inference Prediction Relation
author: Michael Kampffmeyer, Nanqing Dong, Xiaodan Liang, Yujia Zhang, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Salient segmentation aims to segment out attention-grabbing regions, a critical yet challenging task and the foundation of many high-level computer vision applications. It requires semantic-aware grouping of pixels into salient regions and benefits from the utilization of global multi-scale contexts to achieve good local reasoning. Previous works often address it as two-class segmentation problems utilizing complicated multi-step procedures including refinement networks and complex graphical models. We argue that semantic salient segmentation can instead be effectively resolved by reformulating it as a simple yet intuitive pixel-pair based connectivity prediction task. Following the intuition that salient objects can be naturally grouped via semantic-aware connectivity between neighboring pixels, we propose a pure Connectivity Net (ConnNet). ConnNet predicts connectivity probabilities of each pixel with its neighboring pixels by leveraging multi-level cascade contexts embedded in the image and long-range pixel relations. We investigate our approach on two tasks, namely salient object segmentation and salient instance-level segmentation, and illustrate that consistent improvements can be obtained by modeling these tasks as connectivity instead of binary segmentation tasks for a variety of network architectures. We achieve state-of-the-art performance, outperforming or being comparable to existing approaches while reducing inference time due to our less complex approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.07836](http://arxiv.org/abs/1804.07836)

##### PDF
[http://arxiv.org/pdf/1804.07836](http://arxiv.org/pdf/1804.07836)

