---
layout: post
title: "Masked Signal Decomposition Using Subspace Representation and Its Applications"
date: 2017-04-25 14:22:44
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Shervin Minaee, Yao Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Signal decomposition is a classical problem in signal processing, which aims to separate an observed signal into two or more components each with its own property. Usually each component is described by its own subspace or dictionary. Extensive research has been done for the case where the components are additive, but in real world applications, the components are often non-additive. For example, an image may consist of a foreground object overlaid on a background, where each pixel either belongs to the foreground or the background. In such a situation, to separate signal components, we need to find a binary mask which shows the location of each component. Therefore it requires to solve a binary optimization problem. Since most of the binary optimization problems are intractable, we relax this problem to the approximated continuous problem, and solve it by alternating optimization technique, which solves the mask and the subspace projection for each component, alternatingly and iteratively. We show the application of the proposed algorithm for three applications: separation of text from background in images, separation of moving objects from a background undergoing global camera motion in videos, separation of sinusoidal and spike components in one dimensional signals. We demonstrate in each case that considering the non-additive nature of the problem can lead to significant improvement.

##### Abstract (translated by Google)
信号分解是信号处理中的一个经典问题，其目的是将观测到的信号分解成两个或更多个分量，每个分量都有自己的属性。通常每个组件都由其自己的子空间或字典来描述。对于组件是可添加的情况已经进行了广泛的研究，但是在现实世界的应用中，组件通常是非添加的。例如，图像可以由覆盖在背景上的前景对象组成，其中每个像素或者属于前景或者背景。在这种情况下，为了分离信号分量，我们需要找到显示每个分量位置的二进制掩码。因此需要解决一个二元优化问题。由于大部分二元优化问题是难以解决的，我们将这个问题放到近似连续问题上，并通过交替优化技术来解决这个问题，交替迭代地求解每个分量的掩模和子空间投影。我们展示了该算法在三个应用中的应用：图像中文本与背景的分离，运动对象与经历视频中全局相机运动的背景的分离，一维信号中正弦和尖峰分量的分离。我们在每种情况下证明，考虑到问题的非附加性可能会导致重大改进。

##### URL
[https://arxiv.org/abs/1704.07711](https://arxiv.org/abs/1704.07711)

##### PDF
[https://arxiv.org/pdf/1704.07711](https://arxiv.org/pdf/1704.07711)

