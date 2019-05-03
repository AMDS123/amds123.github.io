---
layout: post
title: "DPSNet: End-to-end Deep Plane Sweep Stereo"
date: 2019-05-02 00:59:31
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Sunghoon Im, Hae-Gon Jeon, Stephen Lin, In So Kweon
mathjax: true
---

* content
{:toc}

##### Abstract
Multiview stereo aims to reconstruct scene depth from images acquired by a camera under arbitrary motion. Recent methods address this problem through deep learning, which can utilize semantic cues to deal with challenges such as textureless and reflective regions. In this paper, we present a convolutional neural network called DPSNet (Deep Plane Sweep Network) whose design is inspired by best practices of traditional geometry-based approaches for dense depth reconstruction. Rather than directly estimating depth and/or optical flow correspondence from image pairs as done in many previous deep learning methods, DPSNet takes a plane sweep approach that involves building a cost volume from deep features using the plane sweep algorithm, regularizing the cost volume via a context-aware cost aggregation, and regressing the dense depth map from the cost volume. The cost volume is constructed using a differentiable warping process that allows for end-to-end training of the network. Through the effective incorporation of conventional multiview stereo concepts within a deep learning framework, DPSNet achieves state-of-the-art reconstruction results on a variety of challenging datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00538](http://arxiv.org/abs/1905.00538)

##### PDF
[http://arxiv.org/pdf/1905.00538](http://arxiv.org/pdf/1905.00538)

