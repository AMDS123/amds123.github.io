---
layout: post
title: "Towards Real-Time Accurate Object Detection in Both Images and Videos Based on Dual Refinement"
date: 2018-12-17 10:02:44
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Xingyu Chen, Junzhi Yu, Shihan Kong, Zhengxing Wu, Li Wen
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection has been vigorously studied for years but fast accurate detection for real-world applications remains a very challenging problem: i) Most existing methods have either high accuracy or fast speed; ii) Most prior-art approaches focus on static images, ignoring temporal information in real-world scenes. Overcoming drawbacks of single-stage detectors, we take aim at precisely detecting objects in both images and videos in real time. Firstly, as a dual refinement mechanism, a novel anchor-offset detection including an anchor refinement, a feature offset refinement, and a deformable detection head is designed for two-step regression and capturing accurate detection features. Based on the anchor-offset detection, a dual refinement network (DRN) is developed for high-performance static detection, where a multi-deformable head is further designed to leverage contextual information for describing objects. As for video detection, temporal refinement networks (TRN) and temporal dual refinement networks (TDRN) are developed by propagating the refinement information across time. Our proposed methods are evaluated on PASCAL VOC, COCO, and ImageNet VID datasets. Extensive comparison on static and temporal detection validate the superiority of the DRN, TRN and TDRN. Consequently, our developed approaches achieve a significantly enhanced detection accuracy and make prominent progress in accuracy vs. speed trade-off. Codes will be publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.08638](http://arxiv.org/abs/1807.08638)

##### PDF
[http://arxiv.org/pdf/1807.08638](http://arxiv.org/pdf/1807.08638)

