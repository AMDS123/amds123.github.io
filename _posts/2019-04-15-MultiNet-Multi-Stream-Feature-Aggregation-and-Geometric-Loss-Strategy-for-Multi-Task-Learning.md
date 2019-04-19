---
layout: post
title: "MultiNet++: Multi-Stream Feature Aggregation and Geometric Loss Strategy for Multi-Task Learning"
date: 2019-04-15 19:25:59
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Sumanth Chennupati, Ganesh Sistu, Senthil Yogamani, Samir A Rawashdeh
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-task learning is commonly used in autonomous driving for solving various visual perception tasks. It offers significant benefits in terms of both performance and computational complexity. Current work on multi-task learning networks focus on processing a single input image and there is no known implementation of multi-task learning handling a sequence of images. In this work, we propose a multi-stream multi-task network to take advantage of using feature representations from preceding frames in a video sequence for joint learning of segmentation, depth, and motion. The weights of the current and previous encoder are shared so that features computed in the previous frame can be leveraged without additional computation. In addition, we propose to use the geometric mean of task losses as a better alternative to the weighted average of task losses. The proposed loss function facilitates better handling of the difference in convergence rates of different tasks. Experimental results on KITTI, Cityscapes and SYNTHIA datasets demonstrate that the proposed strategies outperform various existing multi-task learning solutions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08492](http://arxiv.org/abs/1904.08492)

##### PDF
[http://arxiv.org/pdf/1904.08492](http://arxiv.org/pdf/1904.08492)

