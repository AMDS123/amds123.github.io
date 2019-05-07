---
layout: post
title: "Dynamic Zoom-in Network for Fast Object Detection in Large Images"
date: 2018-03-27 15:10:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Reinforcement_Learning Detection
author: Mingfei Gao, Ruichi Yu, Ang Li, Vlad I. Morariu, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a generic framework that reduces the computational cost of object detection while retaining accuracy for scenarios where objects with varied sizes appear in high resolution images. Detection progresses in a coarse-to-fine manner, first on a down-sampled version of the image and then on a sequence of higher resolution regions identified as likely to improve the detection accuracy. Built upon reinforcement learning, our approach consists of a model (R-net) that uses coarse detection results to predict the potential accuracy gain for analyzing a region at a higher resolution and another model (Q-net) that sequentially selects regions to zoom in. Experiments on the Caltech Pedestrians dataset show that our approach reduces the number of processed pixels by over 50% without a drop in detection accuracy. The merits of our approach become more significant on a high resolution test set collected from YFCC100M dataset, where our approach maintains high detection performance while reducing the number of processed pixels by about 70% and the detection time by over 50%.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.05187](https://arxiv.org/abs/1711.05187)

##### PDF
[https://arxiv.org/pdf/1711.05187](https://arxiv.org/pdf/1711.05187)

