---
layout: post
title: "Fast 3D Line Segment Detection From Unorganized Point Cloud"
date: 2019-01-08 21:51:51
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Detection
author: Xiaohu Lu, Yahui Liu, Kai Li
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a very simple but efficient algorithm for 3D line segment detection from large scale unorganized point cloud. Unlike traditional methods which usually extract 3D edge points first and then link them to fit for 3D line segments, we propose a very simple 3D line segment detection algorithm based on point cloud segmentation and 2D line detection. Given the input unorganized point cloud, three steps are performed to detect 3D line segments. Firstly, the point cloud is segmented into 3D planes via region growing and region merging. Secondly, for each 3D plane, all the points belonging to it are projected onto the plane itself to form a 2D image, which is followed by 2D contour extraction and Least Square Fitting to get the 2D line segments. Those 2D line segments are then re-projected onto the 3D plane to get the corresponding 3D line segments. Finally, a post-processing procedure is proposed to eliminate outliers and merge adjacent 3D line segments. Experiments on several public datasets demonstrate the efficiency and robustness of our method. More results and the C++ source code of the proposed algorithm are publicly available at https://github.com/xiaohulugo/3DLineDetection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02532](http://arxiv.org/abs/1901.02532)

##### PDF
[http://arxiv.org/pdf/1901.02532](http://arxiv.org/pdf/1901.02532)

