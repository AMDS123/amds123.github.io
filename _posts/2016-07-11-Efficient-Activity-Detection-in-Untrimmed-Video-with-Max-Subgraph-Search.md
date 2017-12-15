---
layout: post
title: "Efficient Activity Detection in Untrimmed Video with Max-Subgraph Search"
date: 2016-07-11 03:48:21
categories: arXiv_CV
tags: arXiv_CV Detection
author: Chao-Yeh Chen, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an efficient approach for activity detection in video that unifies activity categorization with space-time localization. The main idea is to pose activity detection as a maximum-weight connected subgraph problem. Offline, we learn a binary classifier for an activity category using positive video exemplars that are "trimmed" in time to the activity of interest. Then, given a novel \emph{untrimmed} video sequence, we decompose it into a 3D array of space-time nodes, which are weighted based on the extent to which their component features support the learned activity model. To perform detection, we then directly localize instances of the activity by solving for the maximum-weight connected subgraph in the test video's space-time graph. We show that this detection strategy permits an efficient branch-and-cut solution for the best-scoring---and possibly non-cubically shaped---portion of the video for a given activity classifier. The upshot is a fast method that can search a broader space of space-time region candidates than was previously practical, which we find often leads to more accurate detection. We demonstrate the proposed algorithm on four datasets, and we show its speed and accuracy advantages over multiple existing search strategies.

##### Abstract (translated by Google)
我们提出了一种有效的视频活动检测方法，将活动分类与时空本地化相结合。主要思想是将活动检测作为最大权重连通子图问题。离线时，我们学习了一个活动类别的二元分类器，使用积极的视频范例，可以及时“修剪”到感兴趣的活动中。然后，给定一个新颖的视频序列，我们将其分解成一个三维空间节点阵列，根据其组件特征支持学习活动模型的程度进行加权。为了执行检测，我们通过求解测试视频的时空图中的最大权重连通子图来直接本地化活动的实例。我们表明，这种检测策略允许一个有效的分支和剪切解决方案的最佳评分---可能是非立方体形状---给定活动分类器的视频部分。结果是一个快速的方法，可以搜索比以前实际更广泛的时空区域候选空间，我们发现经常会导致更准确的检测。我们在四个数据集上演示所提出的算法，并且显示其速度和准确度优于多个现有搜索策略的优点。

##### URL
[https://arxiv.org/abs/1607.02815](https://arxiv.org/abs/1607.02815)

##### PDF
[https://arxiv.org/pdf/1607.02815](https://arxiv.org/pdf/1607.02815)

