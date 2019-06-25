---
layout: post
title: "Adaptive Period Embedding for Representing Oriented Objects in Aerial Images"
date: 2019-06-22 13:40:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Embedding Detection
author: Yixing Zhu, Xueqing Wu, Jun Du
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method for representing oriented objects in aerial images named Adaptive Period Embedding (APE). While traditional object detection methods represent object with horizontal bounding boxes, the objects in aerial images are oritented. Calculating the angle of object is an yet challenging task. While almost all previous object detectors for aerial images directly regress the angle of objects, they use complex rules to calculate the angle, and their performance is limited by the rule design. In contrast, our method is based on the angular periodicity of oriented objects. The angle is represented by two two-dimensional periodic vectors whose periods are different, the vector is continuous as shape changes. The label generation rule is more simple and reasonable compared with previous methods. The proposed method is general and can be applied to other oriented detector. Besides, we propose a novel IoU calculation method for long objects named length independent IoU (LIIoU). We intercept part of the long side of the target box to get the maximum IoU between the proposed box and the intercepted target box. Thereby, some long boxes will have corresponding positive samples. Our method reaches the 1st place of DOAI2019 competition task1 (oriented object) held in workshop on Detecting Objects in Aerial Images in conjunction with IEEE CVPR 2019.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09447](http://arxiv.org/abs/1906.09447)

##### PDF
[http://arxiv.org/pdf/1906.09447](http://arxiv.org/pdf/1906.09447)

