---
layout: post
title: "Optical Flow Fields: Dense Correspondence Fields for Highly Accurate Large Displacement Optical Flow Estimation"
date: 2017-03-07 19:28:45
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse
author: Christian Bailer, Bertram Taetz, Didier Stricker
mathjax: true
---

* content
{:toc}

##### Abstract
Modern large displacement optical flow algorithms usually use an initialization by either sparse descriptor matching techniques or dense approximate nearest neighbor fields. While the latter have the advantage of being dense, they have the major disadvantage of being very outlier-prone as they are not designed to find the optical flow, but the visually most similar correspondence. In this article we present a dense correspondence field approach that is much less outlier-prone and thus much better suited for optical flow estimation than approximate nearest neighbor fields. Our approach does not require explicit regularization, smoothing (like median filtering) or a new data term. Instead we solely rely on patch matching techniques and a novel multi-scale matching strategy. We also present enhancements for outlier filtering. We show that our approach is better suited for large displacement optical flow estimation than modern descriptor matching techniques. We do so by initializing EpicFlow with our approach instead of their originally used state-of-the-art descriptor matching technique. We significantly outperform the original EpicFlow on MPI-Sintel, KITTI 2012, KITTI 2015 and Middlebury. In this extended article of our former conference publication we further improve our approach in matching accuracy as well as runtime and present more experiments and insights.

##### Abstract (translated by Google)
现代大位移光流算法通常使用稀疏描述符匹配技术或稠密近似最近邻域进行初始化。虽然后者具有密集的优点，但是由于它们没有被设计用于找到光流，而是在视觉上最相似的对应关系，所以它们具有非常异常的主要缺点。在这篇文章中，我们提出一个密集的通信领域的方法，这是远远少于异常，因此比近似最近邻域更适合光流估计。我们的方法不需要显式正则化，平滑（如中值滤波）或新的数据项。相反，我们完全依靠补丁匹配技术和一种新颖的多尺度匹配策略。我们还提供了异常过滤的增强功能。我们表明，我们的方法比现代描述符匹配技术更适合于大位移光流估计。我们通过使用我们的方法来初始化EpicFlow，而不是使用最初使用的最先进的描述符匹配技术。我们在MPI-Sintel，KITTI 2012，KITTI 2015和Middlebury上的表现都优于EpicFlow。在我们以前的会议刊物的这篇扩展文章中，我们进一步改进了匹配准确性和运行时间的方法，并提出了更多的实验和见解。

##### URL
[https://arxiv.org/abs/1703.02563](https://arxiv.org/abs/1703.02563)

##### PDF
[https://arxiv.org/pdf/1703.02563](https://arxiv.org/pdf/1703.02563)

