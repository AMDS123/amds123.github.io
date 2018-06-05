---
layout: post
title: "Bayesian Semantic Instance Segmentation in Open Set World"
date: 2018-06-04 01:16:17
categories: arXiv_CV
tags: arXiv_CV Semantic_Instance_Segmentation Object_Detection Segmentation Optimization Detection
author: Trung Pham, Vijay Kumar B G, Thanh-Toan Do, Gustavo Carneiro, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the instance segmentation task in the open-set conditions, where input images might contain known and unknown object classes. Existing instance segmentation methods require annotating masks for all object instances, which is expensive and even infeasible in realistic scenarios, where the number of categories increases boundlessly. In this paper, we present a novel open-set instance segmentation approach to segment all object instances in images. Based on the output of an object detector/segmenter trained on known classes, we seek a global image segmentation, whose regions are each assigned to one of the known or unknown classes. We formulate the problem in a Bayesian framework, and approximate the posterior distribution using a simulated annealing optimization equipped with an efficient image partition sampler. We show empirically that our method is competitive with state-of-the-art supervised methods on known classes, but also performs well on unknown classes when compared with unsupervised methods.

##### Abstract (translated by Google)
本文讨论了开放条件下的实例分割任务，其中输入图像可能包含已知和未知对象类。现有的实例分割方法需要为所有对象实例注释掩码，这在实际情况下是昂贵的甚至不可行的，其中类别数量无限增加。在本文中，我们提出了一种新颖的开放式实例分割方法来分割图像中的所有对象实例。基于在已知类别上训练的物体检测器/分段器的输出，我们寻求全局图像分割，其区域分别被分配给已知类别或未知类别之一。我们在贝叶斯框架中制定问题，并使用配备了高效图像分割采样器的模拟退火优化来近似后验分布。我们经验地显示，我们的方法与已知类别的最先进的监督方法相比具有竞争性，但与未监督方法相比，它在未知类别上表现良好。

##### URL
[http://arxiv.org/abs/1806.00911](http://arxiv.org/abs/1806.00911)

##### PDF
[http://arxiv.org/pdf/1806.00911](http://arxiv.org/pdf/1806.00911)

