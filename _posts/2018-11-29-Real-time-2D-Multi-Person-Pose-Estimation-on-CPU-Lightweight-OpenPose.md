---
layout: post
title: "Real-time 2D Multi-Person Pose Estimation on CPU: Lightweight OpenPose"
date: 2018-11-29 08:05:05
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Daniil Osokin
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we adapt multi-person pose estimation architecture to use it on edge devices. We follow the bottom-up approach from OpenPose, the winner of COCO 2016 Keypoints Challenge, because of its decent quality and robustness to number of people inside the frame. With proposed network design and optimized post-processing code the full solution runs at 28 frames per second (fps) on Intel$\unicode{xAE}$ NUC 6i7KYB mini PC and 26 fps on Core$^{TM}$ i7-6850K CPU. The network model has 4.1M parameters and 9 billions floating-point operations (GFLOPs) complexity, which is just ~15% of the baseline 2-stage OpenPose with almost the same quality. The code and model are available as a part of Intel$\unicode{xAE}$ OpenVINO$^{TM}$ Toolkit.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12004](http://arxiv.org/abs/1811.12004)

##### PDF
[http://arxiv.org/pdf/1811.12004](http://arxiv.org/pdf/1811.12004)

