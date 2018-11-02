---
layout: post
title: "Towards Highly Accurate and Stable Face Alignment for High-Resolution Videos"
date: 2018-11-01 12:35:09
categories: arXiv_CV
tags: arXiv_CV Face Pose_Estimation
author: Ying Tai, Yicong Liang, Xiaoming Liu, Lei Duan, Jilin Li, Chengjie Wang, Feiyue Huang, Yu Chen
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, heatmap regression based models have shown their effectiveness in face alignment and pose estimation. However, Conventional Heatmap Regression (CHR) is not accurate nor stable when dealing with high-resolution facial videos, since it finds the maximum activated location in heatmaps which are generated from rounding coordinates, and thus leads to quantization errors when scaling back to the original high-resolution space. In this paper, we propose a Fractional Heatmap Regression (FHR) for high-resolution video-based face alignment. The proposed FHR can accurately estimate the fractional part according to the 2D Gaussian function by sampling three points in heatmaps. To further stabilize the landmarks among continuous video frames while maintaining the precise at the same time, we propose a novel stabilization loss that contains two terms to address time delay and non-smooth issues, respectively. Experiments on 300W, 300-VW and Talking Face datasets clearly demonstrate that the proposed method is more accurate and stable than the state-of-the-art models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00342](http://arxiv.org/abs/1811.00342)

##### PDF
[http://arxiv.org/pdf/1811.00342](http://arxiv.org/pdf/1811.00342)

