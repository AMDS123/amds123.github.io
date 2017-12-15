---
layout: post
title: "Flow Fields: Dense Correspondence Fields for Highly Accurate Large Displacement Optical Flow Estimation"
date: 2015-10-20 13:47:15
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse
author: Christian Bailer, Bertram Taetz, Didier Stricker
mathjax: true
---

* content
{:toc}

##### Abstract
Modern large displacement optical flow algorithms usually use an initialization by either sparse descriptor matching techniques or dense approximate nearest neighbor fields. While the latter have the advantage of being dense, they have the major disadvantage of being very outlier prone as they are not designed to find the optical flow, but the visually most similar correspondence. In this paper we present a dense correspondence field approach that is much less outlier prone and thus much better suited for optical flow estimation than approximate nearest neighbor fields. Our approach is conceptually novel as it does not require explicit regularization, smoothing (like median filtering) or a new data term, but solely our novel purely data based search strategy that finds most inliers (even for small objects), while it effectively avoids finding outliers. Moreover, we present novel enhancements for outlier filtering. We show that our approach is better suited for large displacement optical flow estimation than state-of-the-art descriptor matching techniques. We do so by initializing EpicFlow (so far the best method on MPI-Sintel) with our Flow Fields instead of their originally used state-of-the-art descriptor matching technique. We significantly outperform the original EpicFlow on MPI-Sintel, KITTI and Middlebury.

##### Abstract (translated by Google)
现代大位移光流算法通常使用稀疏描述符匹配技术或稠密近似最近邻域进行初始化。虽然后者具有密集的优点，但是由于它们不是设计用于寻找光流，而是在视觉上最相似的对应关系，所以它们具有非常异常的主要缺点。在本文中，我们提出了一种密集的对应场方法，这种方法的离群值更小，因此比近似最近邻场更适合于光流估计。我们的方法在概念上是新颖的，因为它不需要显式的正则化，平滑（如中值滤波）或新的数据项，而只是我们的新颖的基于数据的搜索策略，即使对于小对象也能找到大部分内容（尽管它有效地避免了发现异常值。此外，我们提出了异常过滤的新增强。我们表明，我们的方法比现有的描述符匹配技术更适合于大位移光流估计。我们通过初始化EpicFlow（到目前为止MPI-Sintel上最好的方法），而不是使用最初使用的最先进的描述符匹配技术。在MPI-Sintel，KITTI和Middlebury，我们的表现明显优于原始的EpicFlow。

##### URL
[https://arxiv.org/abs/1508.05151](https://arxiv.org/abs/1508.05151)

##### PDF
[https://arxiv.org/pdf/1508.05151](https://arxiv.org/pdf/1508.05151)

