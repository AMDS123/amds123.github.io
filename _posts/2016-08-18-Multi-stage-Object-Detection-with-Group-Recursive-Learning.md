---
layout: post
title: "Multi-stage Object Detection with Group Recursive Learning"
date: 2016-08-18 02:37:28
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Classification Detection Relation
author: Jianan Li, Xiaodan Liang, Jianshu Li, Tingfa Xu, Jiashi Feng, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Most of existing detection pipelines treat object proposals independently and predict bounding box locations and classification scores over them separately. However, the important semantic and spatial layout correlations among proposals are often ignored, which are actually useful for more accurate object detection. In this work, we propose a new EM-like group recursive learning approach to iteratively refine object proposals by incorporating such context of surrounding proposals and provide an optimal spatial configuration of object detections. In addition, we propose to incorporate the weakly-supervised object segmentation cues and region-based object detection into a multi-stage architecture in order to fully exploit the learned segmentation features for better object detection in an end-to-end way. The proposed architecture consists of three cascaded networks which respectively learn to perform weakly-supervised object segmentation, object proposal generation and recursive detection refinement. Combining the group recursive learning and the multi-stage architecture provides competitive mAPs of 78.6% and 74.9% on the PASCAL VOC2007 and VOC2012 datasets respectively, which outperforms many well-established baselines [10] [20] significantly.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1608.05159](https://arxiv.org/abs/1608.05159)

##### PDF
[https://arxiv.org/pdf/1608.05159](https://arxiv.org/pdf/1608.05159)

