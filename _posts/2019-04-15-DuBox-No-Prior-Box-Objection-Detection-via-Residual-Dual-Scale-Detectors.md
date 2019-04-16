---
layout: post
title: "DuBox: No-Prior Box Objection Detection via Residual Dual Scale Detectors"
date: 2019-04-15 07:32:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Shuai Chen, Jinpeng Li, Chuanqi Yao, Wenbo Hou, Shuo Qin, Wenyao Jin, Tang Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional neural objection detection methods use multi-scale features that allow multiple detectors to perform detecting tasks independently and in parallel. At the same time, with the handling of the prior box, the algorithm's ability to deal with scale invariance is enhanced. However, too many prior boxes and independent detectors will increase the computational redundancy of the detection algorithm. In this study, we introduce Dubox, a new one-stage approach that detects the objects without prior box. Working with multi-scale features, the designed dual scale residual unit makes dual scale detectors no longer run independently. The second scale detector learns the residual of the first. Dubox has enhanced the capacity of heuristic-guided that can further enable the first scale detector to maximize the detection of small targets and the second to detect objects that cannot be identified by the first one. Besides, for each scale detector, with the new classification-regression progressive strapped loss makes our process not based on prior boxes. Integrating these strategies, our detection algorithm has achieved excellent performance in terms of speed and accuracy. Extensive experiments on the VOC, COCO object detection benchmark have confirmed the effectiveness of this algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06883](http://arxiv.org/abs/1904.06883)

##### PDF
[http://arxiv.org/pdf/1904.06883](http://arxiv.org/pdf/1904.06883)

