---
layout: post
title: "Hybrid Task Cascade for Instance Segmentation"
date: 2019-01-22 18:50:36
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection Relation
author: Kai Chen, Jiangmiao Pang, Jiaqi Wang, Yu Xiong, Xiaoxiao Li, Shuyang Sun, Wansen Feng, Ziwei Liu, Jianping Shi, Wanli Ouyang, Chen Change Loy, Dahua Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Cascade is a classic yet powerful architecture that has boosted performance on various tasks. However, how to introduce cascade to instance segmentation remains an open question. A simple combination of Cascade R-CNN and Mask R-CNN only brings limited gain. In exploring a more effective approach, we find that the key to a successful instance segmentation cascade is to fully leverage the reciprocal relationship between detection and segmentation. In this work, we propose a new framework, Hybrid Task Cascade (HTC), which differs in two important aspects: (1) instead of performing cascaded refinement on these two tasks separately, it interweaves them for a joint multi-stage processing; (2) it adopts a fully convolutional branch to provide spatial context, which can help distinguishing hard foreground from cluttered background. Overall, this framework can learn more discriminative features progressively while integrating complementary features together in each stage. Without bells and whistles, a single HTC obtains 38.4% and 1.5% improvement over a strong Cascade Mask R-CNN baseline on MSCOCO dataset. More importantly, our overall system achieves 48.6 mask AP on the test-challenge dataset and 49.0 mask AP on test-dev, which are the state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07518](http://arxiv.org/abs/1901.07518)

##### PDF
[http://arxiv.org/pdf/1901.07518](http://arxiv.org/pdf/1901.07518)

