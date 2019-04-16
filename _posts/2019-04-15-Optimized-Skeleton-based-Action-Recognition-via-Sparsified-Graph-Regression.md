---
layout: post
title: "Optimized Skeleton-based Action Recognition via Sparsified Graph Regression"
date: 2019-04-15 05:33:09
categories: arXiv_CV
tags: arXiv_CV Attention Action_Recognition CNN Optimization RNN Recognition
author: Xiang Gao, Wei Hu, Jiaxiang Tang, Jiaying Liu, Zongming Guo
mathjax: true
---

* content
{:toc}

##### Abstract
With the prevalence of accessible depth sensors, dynamic human body skeletons have attracted much attention as a robust modality for action recognition. Previous methods model skeletons based on RNN or CNN, which has limited expressive power for irregular skeleton joints. While graph convolutional networks (GCN) have been proposed to address irregular graph-structured data, the fundamental graph construction remains challenging. In this paper, we represent skeletons naturally on graphs, and propose a graph regression based GCN (GR-GCN) for skeleton-based action recognition, aiming to capture the spatio-temporal variation in the data. As the graph representation is crucial to graph convolution, we first propose graph regression to statistically learn the underlying graph from multiple observations. In particular, we provide spatio-temporal modeling of skeletons and pose an optimization problem on the graph structure over consecutive frames, which enforces the sparsity of the underlying graph for efficient representation. The optimized graph not only connects each joint to its neighboring joints in the same frame strongly or weakly, but also links with relevant joints in the previous and subsequent frames. We then feed the optimized graph into the GCN along with the coordinates of the skeleton sequence for feature learning, where we deploy high-order and fast Chebyshev approximation of spectral graph convolution. Further, we provide analysis of the variation characterization by the Chebyshev approximation. Experimental results validate the effectiveness of the proposed graph regression and show that the proposed GR-GCN achieves the state-of-the-art performance on the widely used NTU RGB+D, UT-Kinect and SYSU 3D datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12013](http://arxiv.org/abs/1811.12013)

##### PDF
[http://arxiv.org/pdf/1811.12013](http://arxiv.org/pdf/1811.12013)

