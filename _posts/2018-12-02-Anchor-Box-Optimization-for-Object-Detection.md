---
layout: post
title: "Anchor Box Optimization for Object Detection"
date: 2018-12-02 21:30:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Inference Detection Gradient_Descent
author: Yuanyi Zhong, Jianfeng Wang, Jian Peng, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a general approach to optimize anchor boxes for object detection. Nowadays, anchor boxes are widely adopted in state-of-the-art detection frameworks. However, all these frameworks pre-define anchor box shapes in a heuristic way and fix the size during training. To improve the accuracy and reduce the effort to design the anchor boxes, we propose to dynamically learn the shapes, which allows the anchors to automatically adapt to the data distribution and the network learning capability. The learning approach can be easily implemented in the stochastic gradient descent way and be plugged into any anchor box-based detection framework. The extra training cost is almost negligible and it has no impact on the inference time cost. Exhaustive experiments also demonstrate that the proposed anchor optimization method consistently achieves significant improvement ($\ge 1\%$ mAP absolute gain) over the baseline method on several benchmark datasets including Pascal VOC 07+12, MS COCO and Brainwash. Meanwhile, the robustness is also verified towards different anchor box initialization methods, which greatly simplifies the problem of anchor box design.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00469](http://arxiv.org/abs/1812.00469)

##### PDF
[http://arxiv.org/pdf/1812.00469](http://arxiv.org/pdf/1812.00469)

