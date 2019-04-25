---
layout: post
title: "LFFD: A Light and Fast Face Detector for Edge Devices"
date: 2019-04-24 03:47:24
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Inference Detection Face_Detection Relation
author: Yonghao He, Dezhong Xu, Lifang Wu, Meng Jian, Shiming Xiang, Chunhong Pan
mathjax: true
---

* content
{:toc}

##### Abstract
Face detection, as a fundamental technology for various applications, is always deployed on edge devices. There-fore, face detectors are supposed to have limited model size and fast inference speed. This paper introduces a Light and Fast Face Detector (LFFD) for edge devices. We rethink the receptive field (RF) in context of face detection and find that RFs can be used as inherent anchors instead of manually construction. Combining RF anchors and appropriate strides, the proposed method can cover a large range of continuous face scales with nearly 100% hit rate, rather than discrete scales. The insightful understanding of relations between effective receptive field (ERF) and face scales motivates an efficient backbone for one-stage detection. The backbone is characterized by eight detection branches and common building blocks, resulting in efficient computation. Comprehensive and extensive experiments on popular benchmarks: WIDER FACE and FDDB are conducted. A new evaluation schema is proposed for practical applications. Under the new schema, the proposed method can achieve superior accuracy (WIDER FACE Val/Test - Easy: 0.910/0.896, Medium: 0.880/0.865, Hard: 0.780/0.770; FDDB - discontinuous: 0.965, continuous: 0.719). Multiple hardware platforms are introduced to evaluate the running efficiency. The proposed methods can obtain fast inference speed (NVIDIA TITAN Xp: 131.45 FPS at 640480; NVIDIA TX2: 136.99 FPS at 160120; Raspberry Pi 3 Model B+: 8.44 FPS at 160120) with model size of 9 MB.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10633](http://arxiv.org/abs/1904.10633)

##### PDF
[http://arxiv.org/pdf/1904.10633](http://arxiv.org/pdf/1904.10633)

