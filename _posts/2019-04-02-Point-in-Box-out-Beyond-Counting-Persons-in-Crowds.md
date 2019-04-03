---
layout: post
title: "Point in, Box out: Beyond Counting Persons in Crowds"
date: 2019-04-02 11:03:32
categories: arXiv_CV
tags: arXiv_CV Face Detection
author: Yuting Liu, Miaojing Shi, Qijun Zhao, Xiaofang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Modern crowd counting methods usually employ deep neural networks (DNN) to estimate crowd counts via density regression. Despite their significant improvements, the regression-based methods are incapable of providing the detection of individuals in crowds. The detection-based methods, on the other hand, have not been largely explored in recent trends of crowd counting due to the needs for expensive bounding box annotations. In this work, we instead propose a new deep detection network with only point supervision required. It can simultaneously detect the size and location of human heads and count them in crowds. We first mine useful person size information from point-level annotations and initialize the pseudo ground truth bounding boxes. An online updating scheme is introduced to refine the pseudo ground truth during training; while a locally-constrained regression loss is designed to provide additional constraints on the size of the predicted boxes in a local neighborhood. In the end, we propose a curriculum learning strategy to train the network from images of relatively accurate and easy pseudo ground truth first. Extensive experiments are conducted in both detection and counting tasks on several standard benchmarks, e.g. ShanghaiTech, UCF_CC_50, WiderFace, and TRANCOS datasets, and the results show the superiority of our method over the state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01333](http://arxiv.org/abs/1904.01333)

##### PDF
[http://arxiv.org/pdf/1904.01333](http://arxiv.org/pdf/1904.01333)

