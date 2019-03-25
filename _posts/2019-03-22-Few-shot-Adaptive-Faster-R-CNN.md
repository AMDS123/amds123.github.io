---
layout: post
title: "Few-shot Adaptive Faster R-CNN"
date: 2019-03-22 06:32:12
categories: arXiv_CV
tags: arXiv_CV Regularization Object_Detection Classification Detection
author: Tao Wang, Xiaopeng Zhang, Li Yuan, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
To mitigate the detection performance drop caused by domain shift, we aim to develop a novel few-shot adaptation approach that requires only a few target domain images with limited bounding box annotations. To this end, we first observe several significant challenges. First, the target domain data is highly insufficient, making most existing domain adaptation methods ineffective. Second, object detection involves simultaneous localization and classification, further complicating the model adaptation process. Third, the model suffers from over-adaptation (similar to overfitting when training with a few data example) and instability risk that may lead to degraded detection performance in the target domain. To address these challenges, we first introduce a pairing mechanism over source and target features to alleviate the issue of insufficient target domain samples. We then propose a bi-level module to adapt the source trained detector to the target domain: 1) the split pooling based image level adaptation module uniformly extracts and aligns paired local patch features over locations, with different scale and aspect ratio; 2) the instance level adaptation module semantically aligns paired object features while avoids inter-class confusion. Meanwhile, a source model feature regularization (SMFR) is applied to stabilize the adaptation process of the two modules. Combining these contributions gives a novel few-shot adaptive Faster-RCNN framework, termed FAFRCNN, which effectively adapts to target domain with a few labeled samples. Experiments with multiple datasets show that our model achieves new state-of-the-art performance under both the interested few-shot domain adaptation(FDA) and unsupervised domain adaptation(UDA) setting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09372](http://arxiv.org/abs/1903.09372)

##### PDF
[http://arxiv.org/pdf/1903.09372](http://arxiv.org/pdf/1903.09372)

