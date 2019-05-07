---
layout: post
title: "Scalable, High-Quality Object Detection"
date: 2015-12-09 03:41:42
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection
author: Christian Szegedy, Scott Reed, Dumitru Erhan, Dragomir Anguelov, Sergey Ioffe
mathjax: true
---

* content
{:toc}

##### Abstract
Current high-quality object detection approaches use the scheme of salience-based object proposal methods followed by post-classification using deep convolutional features. This spurred recent research in improving object proposal methods. However, domain agnostic proposal generation has the principal drawback that the proposals come unranked or with very weak ranking, making it hard to trade-off quality for running time. This raises the more fundamental question of whether high-quality proposal generation requires careful engineering or can be derived just from data alone. We demonstrate that learning-based proposal methods can effectively match the performance of hand-engineered methods while allowing for very efficient runtime-quality trade-offs. Using the multi-scale convolutional MultiBox (MSC-MultiBox) approach, we substantially advance the state-of-the-art on the ILSVRC 2014 detection challenge data set, with $0.5$ mAP for a single model and $0.52$ mAP for an ensemble of two models. MSC-Multibox significantly improves the proposal quality over its predecessor MultiBox~method: AP increases from $0.42$ to $0.53$ for the ILSVRC detection challenge. Finally, we demonstrate improved bounding-box recall compared to Multiscale Combinatorial Grouping with less proposals on the Microsoft-COCO data set.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1412.1441](https://arxiv.org/abs/1412.1441)

##### PDF
[https://arxiv.org/pdf/1412.1441](https://arxiv.org/pdf/1412.1441)

