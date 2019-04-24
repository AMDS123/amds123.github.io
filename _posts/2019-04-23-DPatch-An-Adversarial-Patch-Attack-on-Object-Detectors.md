---
layout: post
title: "DPatch: An Adversarial Patch Attack on Object Detectors"
date: 2019-04-23 16:44:32
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Knowledge Classification Prediction Detection
author: Xin Liu, Huanrui Yang, Ziwei Liu, Linghao Song, Hai Li, Yiran Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Object detectors have emerged as an indispensable module in modern computer vision systems. In this work, we propose DPatch -- a black-box adversarial-patch-based attack towards mainstream object detectors (i.e. Faster R-CNN and YOLO). Unlike the original adversarial patch that only manipulates image-level classifier, our DPatch simultaneously attacks the bounding box regression and object classification so as to disable their predictions. Compared to prior works, DPatch has several appealing properties: (1) DPatch can perform both untargeted and targeted effective attacks, degrading the mAP of Faster R-CNN and YOLO from 75.10% and 65.7% down to below 1%, respectively. (2) DPatch is small in size and its attacking effect is location-independent, making it very practical to implement real-world attacks. (3) DPatch demonstrates great transferability among different detectors as well as training datasets. For example, DPatch that is trained on Faster R-CNN can effectively attack YOLO, and vice versa. Extensive evaluations imply that DPatch can perform effective attacks under black-box setup, i.e., even without the knowledge of the attacked network's architectures and parameters. Successful realization of DPatch also illustrates the intrinsic vulnerability of the modern detector architectures to such patch-based adversarial attacks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.02299](http://arxiv.org/abs/1806.02299)

##### PDF
[http://arxiv.org/pdf/1806.02299](http://arxiv.org/pdf/1806.02299)

