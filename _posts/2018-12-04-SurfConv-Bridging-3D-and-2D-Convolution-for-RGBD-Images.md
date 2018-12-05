---
layout: post
title: "SurfConv: Bridging 3D and 2D Convolution for RGBD Images"
date: 2018-12-04 16:42:29
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Semantic_Segmentation Recognition
author: Hang Chu, Wei-Chiu Ma, Kaustav Kundu, Raquel Urtasun, Sanja Fidler
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the problem of using 3D information in convolutional neural networks for down-stream recognition tasks. Using depth as an additional channel alongside the RGB input has the scale variance problem present in image convolution based approaches. On the other hand, 3D convolution wastes a large amount of memory on mostly unoccupied 3D space, which consists of only the surface visible to the sensor. Instead, we propose SurfConv, which "slides" compact 2D filters along the visible 3D surface. SurfConv is formulated as a simple depth-aware multi-scale 2D convolution, through a new Data-Driven Depth Discretization (D4) scheme. We demonstrate the effectiveness of our method on indoor and outdoor 3D semantic segmentation datasets. Our method achieves state-of-the-art performance with less than 30% parameters used by the 3D convolution-based approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01519](http://arxiv.org/abs/1812.01519)

##### PDF
[http://arxiv.org/pdf/1812.01519](http://arxiv.org/pdf/1812.01519)

