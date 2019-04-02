---
layout: post
title: "TAN: Temporal Affine Network for Real-Time Left Ventricle Anatomical Structure Analysis Based on 2D Ultrasound Videos"
date: 2019-04-01 08:23:32
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Detection Recognition
author: Sihong Chen, Kai Ma, Yefeng Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
With superiorities on low cost, portability, and free of radiation, echocardiogram is a widely used imaging modality for left ventricle (LV) function quantification. However, automatic LV segmentation and motion tracking is still a challenging task. In addition to fuzzy border definition, low contrast, and abounding artifacts on typical ultrasound images, the shape and size of the LV change significantly in a cardiac cycle. In this work, we propose a temporal affine network (TAN) to perform image analysis in a warped image space, where the shape and size variations due to the cardiac motion as well as other artifacts are largely compensated. Furthermore, we perform three frequent echocardiogram interpretation tasks simultaneously: standard cardiac plane recognition, LV landmark detection, and LV segmentation. Instead of using three networks with one dedicating to each task, we use a multi-task network to perform three tasks simultaneously. Since three tasks share the same encoder, the compact network improves the segmentation accuracy with more supervision. The network is further finetuned with optical flow adjusted annotations to enhance motion coherence in the segmentation result. Experiments on 1,714 2D echocardiographic sequences demonstrate that the proposed method achieves state-of-the-art segmentation accuracy with real-time efficiency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00631](http://arxiv.org/abs/1904.00631)

##### PDF
[http://arxiv.org/pdf/1904.00631](http://arxiv.org/pdf/1904.00631)

