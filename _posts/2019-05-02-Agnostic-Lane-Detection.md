---
layout: post
title: "Agnostic Lane Detection"
date: 2019-05-02 05:58:17
categories: arXiv_AI
tags: arXiv_AI Segmentation Semantic_Segmentation Detection
author: Yuenan Hou
mathjax: true
---

* content
{:toc}

##### Abstract
Lane detection is an important yet challenging task in autonomous driving, which is affected by many factors, e.g., light conditions, occlusions caused by other vehicles, irrelevant markings on the road and the inherent long and thin property of lanes. Conventional methods typically treat lane detection as a semantic segmentation task, which assigns a class label to each pixel of the image. This formulation heavily depends on the assumption that the number of lanes is pre-defined and fixed and no lane changing occurs, which does not always hold. To make the lane detection model applicable to an arbitrary number of lanes and lane changing scenarios, we adopt an instance segmentation approach, which first differentiates lanes and background and then classify each lane pixel into each lane instance. Besides, a multi-task learning paradigm is utilized to better exploit the structural information and the feature pyramid architecture is used to detect extremely thin lanes. Three popular lane detection benchmarks, i.e., TuSimple, CULane and BDD100K, are used to validate the effectiveness of our proposed algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03704](http://arxiv.org/abs/1905.03704)

##### PDF
[http://arxiv.org/pdf/1905.03704](http://arxiv.org/pdf/1905.03704)

