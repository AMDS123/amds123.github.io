---
layout: post
title: "Revisiting Perspective Information for Efficient Crowd Counting"
date: 2018-12-09 19:26:07
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN
author: Miaojing Shi, Zhaohui Yang, Chao Xu, Qijun Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Crowd counting is the task of estimating people numbers in crowd images. Modern crowd counting methods employ deep neural networks to estimate crowd counts via crowd density regressions. A major challenge of this task lies in the perspective distortion, which results in drastic person scale change in an image. Density regression on the small person area is in general very hard. In this work, we propose a perspective-aware convolutional neural network (PACNN) for efficient crowd counting, which integrates the perspective information into density regression to provide additional knowledge of the person scale change in an image. Ground truth perspective maps are firstly generated for training; PACNN is then specifically designed to predict multi-scale perspective maps, and encode them as perspective-aware weighting layers in the network to adaptively combine the outputs of multi-scale density maps. The weights are learned at every pixel of the maps such that the final density combination is robust to the perspective distortion. We conduct extensive experiments on the ShanghaiTech, WorldExpo'10, UCF_CC_50, and UCSD datasets, and demonstrate the effectiveness and efficiency of PACNN over the state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.01989](http://arxiv.org/abs/1807.01989)

##### PDF
[http://arxiv.org/pdf/1807.01989](http://arxiv.org/pdf/1807.01989)

