---
layout: post
title: "Generalized Graph Convolutional Networks for Skeleton-based Action Recognition"
date: 2018-11-29 08:36:18
categories: arXiv_CV
tags: arXiv_CV Attention Action_Recognition CNN RNN Recognition
author: Xiang Gao, Wei Hu, Jiaxiang Tang, Pan Pan, Jiaying Liu, Zongming Guo
mathjax: true
---

* content
{:toc}

##### Abstract
With the prevalence of accessible depth sensors, dynamic human body skeletons have attracted much attention as a robust modality for action recognition. Previous methods model skeletons based on RNN or CNN, which has limited expressive power for irregular joints. In this paper, we represent skeletons naturally on graphs and propose a generalized graph convolutional neural networks (GGCN) for skeleton-based action recognition, aiming to capture space-time variation via spectral graph theory. In particular, we construct a generalized graph over consecutive frames, where each joint is not only connected to its neighboring joints in the same frame strongly or weakly, but also linked with relevant joints in the previous and subsequent frames. The generalized graphs are then fed into GGCN along with the coordinate matrix of the skeleton sequence for feature learning, where we deploy high-order and fast Chebyshev approximation of spectral graph convolution in the network. Experiments show that we achieve the state-of-the-art performance on the widely used NTU RGB+D, UT-Kinect and SYSU 3D datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12013](http://arxiv.org/abs/1811.12013)

##### PDF
[http://arxiv.org/pdf/1811.12013](http://arxiv.org/pdf/1811.12013)

