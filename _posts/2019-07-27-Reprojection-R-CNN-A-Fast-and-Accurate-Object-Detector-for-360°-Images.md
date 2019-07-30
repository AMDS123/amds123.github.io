---
layout: post
title: "Reprojection R-CNN: A Fast and Accurate Object Detector for 360° Images"
date: 2019-07-27 02:12:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Pengyu Zhao, Ansheng You, Yuanxing Zhang, Jiaying Liu, Kaigui Bian, Yunhai Tong
mathjax: true
---

* content
{:toc}

##### Abstract
360° images are usually represented in either equirectangular projection (ERP) or multiple perspective projections. Different from the flat 2D images, the detection task is challenging for 360° images due to the distortion of ERP and the inefficiency of perspective projections. However, existing methods mostly focus on one of the above representations instead of both, leading to limited detection performance. Moreover, the lack of appropriate bounding-box annotations as well as the annotated datasets further increases the difficulties of the detection task. In this paper, we present a standard object detection framework for 360° images. Specifically, we adapt the terminologies of the traditional object detection task to the omnidirectional scenarios, and propose a novel two-stage object detector, i.e., Reprojection R-CNN by combining both ERP and perspective projection. Owing to the omnidirectional field-of-view of ERP, Reprojection R-CNN first generates coarse region proposals efficiently by a distortion-aware spherical region proposal network. Then, it leverages the distortion-free perspective projection and refines the proposed regions by a novel reprojection network. We construct two novel synthetic datasets for training and evaluation. Experiments reveal that Reprojection R-CNN outperforms the previous state-of-the-art methods on the mAP metric. In addition, the proposed detector could run at 178ms per image in the panoramic datasets, which implies its practicability in real-world applications.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1907.11830](https://arxiv.org/abs/1907.11830)

##### PDF
[https://arxiv.org/pdf/1907.11830](https://arxiv.org/pdf/1907.11830)

