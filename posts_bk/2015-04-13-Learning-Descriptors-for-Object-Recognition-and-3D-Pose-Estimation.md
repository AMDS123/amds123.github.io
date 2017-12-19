---
layout: post
title: "Learning Descriptors for Object Recognition and 3D Pose Estimation"
date: 2015-04-13 13:53:07
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Recognition
author: Paul Wohlhart, Vincent Lepetit
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting poorly textured objects and estimating their 3D pose reliably is still a very challenging problem. We introduce a simple but powerful approach to computing descriptors for object views that efficiently capture both the object identity and 3D pose. By contrast with previous manifold-based approaches, we can rely on the Euclidean distance to evaluate the similarity between descriptors, and therefore use scalable Nearest Neighbor search methods to efficiently handle a large number of objects under a large range of poses. To achieve this, we train a Convolutional Neural Network to compute these descriptors by enforcing simple similarity and dissimilarity constraints between the descriptors. We show that our constraints nicely untangle the images from different objects and different views into clusters that are not only well-separated but also structured as the corresponding sets of poses: The Euclidean distance between descriptors is large when the descriptors are from different objects, and directly related to the distance between the poses when the descriptors are from the same object. These important properties allow us to outperform state-of-the-art object views representations on challenging RGB and RGB-D data.

##### Abstract (translated by Google)
检测质地不好的物体并可靠地估计其三维位置仍然是一个非常具有挑战性的问题。我们引入一个简单而强大的方法来计算对象视图的描述符，从而有效地捕获对象标识和三维姿态。与之前的基于流形的方法相比，我们可以依靠欧几里德距离来评估描述符之间的相似性，因此使用可伸缩的最近邻搜索方法来有效地处理大范围姿势下的大量对象。为了达到这个目的，我们训练一个卷积神经网络，通过强化描述符之间的简单相似和不相似约束来计算这些描述符。我们发现，我们的约束条件很好地将来自不同对象和不同视图的图像解开成不仅分离良好而且还构造为相应的姿势集合的集群：当描述符来自不同的对象时描述符之间的欧几里德距离是大的，直接关系到描述符来自同一个对象时姿态之间的距离。这些重要的属性使我们能够在具有挑战性的RGB和RGB-D数据上超越最先进的对象视图表示。

##### URL
[https://arxiv.org/abs/1502.05908](https://arxiv.org/abs/1502.05908)

##### PDF
[https://arxiv.org/pdf/1502.05908](https://arxiv.org/pdf/1502.05908)

