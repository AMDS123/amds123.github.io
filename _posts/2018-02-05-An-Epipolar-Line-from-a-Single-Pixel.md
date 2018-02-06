---
layout: post
title: "An Epipolar Line from a Single Pixel"
date: 2018-02-05 12:24:43
categories: arXiv_CV
tags: arXiv_CV
author: Tavi Halperin, Michael Werman
mathjax: true
---

* content
{:toc}

##### Abstract
Computing the epipolar geometry from feature points between cameras with very different viewpoints is often error prone, as an object's appearance can vary greatly between images. For such cases, it has been shown that using motion extracted from video can achieve much better results than using a static image. This paper extends these earlier works based on the scene dynamics. In this paper we propose a new method to compute the epipolar geometry from a video stream, by exploiting the following observation: For a pixel p in Image A, all pixels corresponding to p in Image B are on the same epipolar line. Equivalently, the image of the line going through camera A's center and p is an epipolar line in B. Therefore, when cameras A and B are synchronized, the momentary images of two objects projecting to the same pixel, p, in camera A at times t1 and t2, lie on an epipolar line in camera B. Based on this observation we achieve fast and precise computation of epipolar lines. Calibrating cameras based on our method of finding epipolar lines is much faster and more robust than previous methods.

##### Abstract (translated by Google)
从具有非常不同的观察点的相机之间的特征点计算极线几何结构通常是容易出错的，因为在图像之间对象的外观可能变化很大。对于这种情况，已经表明，使用从视频中提取的运动可以获得比使用静态图像好得多的结果。本文基于现场动力学扩展了这些早期的作品。在本文中，我们提出了一种新的方法来从视频流计算极线几何，通过以下观察：对于图像A中的像素p，与图像B中的p相对应的所有像素在相同的极线上。等同地，穿过摄像机A的中心的线和p的图像是B中的极线。因此，当摄像机A和B同步时，两个物体的瞬时图像在时间上在相机A中投影到同一像素p t1和t2位于相机B的极线上。基于这个观察，我们实现了对极线的快速和精确的计算。基于我们找到核线的方法来校准摄像机比以前的方法要快得多，也更稳健。

##### URL
[http://arxiv.org/abs/1703.09725](http://arxiv.org/abs/1703.09725)

##### PDF
[http://arxiv.org/pdf/1703.09725](http://arxiv.org/pdf/1703.09725)

