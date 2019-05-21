---
layout: post
title: "Learning to Count Objects with Few Exemplar Annotations"
date: 2019-05-20 06:28:44
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Jianfeng Wang, Rong Xiao, Yandong Guo, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the problem of object counting with incomplete annotations. Based on the observation that in many object counting problems the target objects are normally repeated and highly similar to each other, we are particularly interested in the setting when only a few exemplar annotations are provided. Directly applying object detection with incomplete annotations will result in severe accuracy degradation due to its improper handling of unlabeled object instances. To address the problem, we propose a positiveness-focused object detector (PFOD) to progressively propagate the incomplete labels before applying the general object detection algorithm. The PFOD focuses on the positive samples and ignore the negative instances at most of the learning time. This strategy, though simple, dramatically boosts the object counting accuracy. On the CARPK dataset for parking lot car counting, we improved mAP@0.5 from 4.58% to 72.44% using only 5 training images each with 5 bounding boxes. On the Drink35 dataset for shelf product counting, the mAP@0.5 is improved from 14.16% to 53.73% using 10 training images each with 5 bounding boxes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07898](http://arxiv.org/abs/1905.07898)

##### PDF
[http://arxiv.org/pdf/1905.07898](http://arxiv.org/pdf/1905.07898)

