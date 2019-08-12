---
layout: post
title: "PosNeg-Balanced Anchors with Aligned Features for Single-Shot Object Detection"
date: 2019-08-09 03:29:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Qiankun Tang, Shice Liu, Jie Li, Yu Hu
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel single-shot object detector to ease the imbalance of foreground-background class by suppressing the easy negatives while increasing the positives. To achieve this, we propose an Anchor Promotion Module (APM) which predicts the probability of each anchor as positive and adjusts their initial locations and shapes to promote both the quality and quantity of positive anchors. In addition, we design an efficient Feature Alignment Module (FAM) to extract aligned features for fitting the promoted anchors with the help of both the location and shape transformation information from the APM. We assemble the two proposed modules to the backbone of VGG-16 and ResNet-101 network with an encoder-decoder architecture. Extensive experiments on MS COCO well demonstrate our model performs competitively with alternative methods (40.0\% mAP on \textit{test-dev} set) and runs faster (28.6 \textit{fps}).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.03295](https://arxiv.org/abs/1908.03295)

##### PDF
[https://arxiv.org/pdf/1908.03295](https://arxiv.org/pdf/1908.03295)

