---
layout: post
title: "YOLACT: Real-time Instance Segmentation"
date: 2019-04-04 17:46:12
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Daniel Bolya, Chong Zhou, Fanyi Xiao, Yong Jae Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple, fully-convolutional model for real-time instance segmentation that achieves 29.8 mAP on MS COCO at 33 fps evaluated on a single Titan Xp, which is significantly faster than any previous competitive approach. Moreover, we obtain this result after training on only one GPU. We accomplish this by breaking instance segmentation into two parallel subtasks: (1) generating a set of prototype masks and (2) predicting per-instance mask coefficients. Then we produce instance masks by linearly combining the prototypes with the mask coefficients. We find that because this process doesn't depend on repooling, this approach produces very high-quality masks and exhibits temporal stability for free. Furthermore, we analyze the emergent behavior of our prototypes and show they learn to localize instances on their own in a translation variant manner, despite being fully-convolutional. Finally, we also propose Fast NMS, a drop-in 12 ms faster replacement for standard NMS that only has a marginal performance penalty.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02689](http://arxiv.org/abs/1904.02689)

##### PDF
[http://arxiv.org/pdf/1904.02689](http://arxiv.org/pdf/1904.02689)

