---
layout: post
title: "Learning to Find Good Correspondences"
date: 2017-11-16 07:54:57
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Kwang Moo Yi, Eduard Trulls, Yuki Ono, Vincent Lepetit, Mathieu Salzmann, Pascal Fua
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a deep architecture to learn to find good correspondences for wide-baseline stereo. Given a set of putative sparse matches and the camera intrinsics, we train our network in an end-to-end fashion to label the correspondences as inliers or outliers, while simultaneously using them to recover the relative pose, as encoded by the essential matrix. Our architecture is based on a multi-layer perceptron operating on pixel coordinates rather than directly on the image, and is thus simple and small. We introduce a novel normalization technique, called Context Normalization, which allows us to process each data point separately while imbuing it with global information, and also makes the network invariant to the order of the correspondences. Our experiments on multiple challenging datasets demonstrate that our method is able to drastically improve the state of the art with little training data.

##### Abstract (translated by Google)
我们开发了一个深层次的体系结构来学习如何找到宽基线立体声的良好对应关系。给定一组假定的稀疏匹配和相机内在因素，我们以端到端的方式训练我们的网络，将对应关系标记为内点或外点，同时使用它们来恢复由基本矩阵编码的相对位姿。我们的体系结构基于多层感知器，基于像素坐标而不是直接在图像上运行，因此简单而小巧。我们引入了一种新的规范化技术，称为上下文规范化（Context Normalization），它允许我们分别处理每个数据点，同时注入全局信息，并且使网络对于对应关系的顺序不变。我们在多个具有挑战性的数据集上的实验表明，我们的方法能够大幅度提高最少的训练数据。

##### URL
[https://arxiv.org/abs/1711.05971](https://arxiv.org/abs/1711.05971)

##### PDF
[https://arxiv.org/pdf/1711.05971](https://arxiv.org/pdf/1711.05971)

