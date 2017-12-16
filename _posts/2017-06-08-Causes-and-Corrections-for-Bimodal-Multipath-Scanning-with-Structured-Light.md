---
layout: post
title: "Causes and Corrections for Bimodal Multipath Scanning with Structured Light"
date: 2017-06-08 18:01:04
categories: arXiv_CV
tags: arXiv_CV Face
author: Yu Zhang, Daniel L. Lau, Ying Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Structured light illumination is an active 3-D scanning technique based on projecting/capturing a set of striped patterns and measuring the warping of the patterns as they reflect off a target object's surface. As designed, each pixel in the camera sees exactly one pixel from the projector; however, there are exceptions to this when the scanned surface has a complicated geometry with step edges and other discontinuities in depth or where the target surface has specularities that reflect light away from the camera. These situations are generally referred to multipath where a given camera pixel receives light from multiple positions from the projector. In the case of bimodal multipath, the camera pixel receives light from exactly two positions from the projector which occurs when light bounce back from a reflective surface or along a step edge where the edge slices through a pixel so that the pixel sees both a foreground and background surface. In this paper, we present a general mathematical model and address the bimodal multipath issue in a phase measuring profilometry scanner to measure the constructive and destructive interference between the two light paths, and by taking advantage of this interesting cue, separate the paths and make two separated depth measurements. We also validate our algorithm with both simulation and a number of challenging real cases.

##### Abstract (translated by Google)
结构光照是一种主动的三维扫描技术，基于投射/捕获一组条纹图案并测量图案在反射离开目标物体表面时的翘曲。按照设计，相机中的每个像素只能看到来自投影机的一个像素;然而，当扫描的表面具有复杂的几何形状并具有阶梯边缘和其他不连续的深度，或者目标表面具有反射远离相机的光的镜面时，这也是例外。这些情况通常被称为多路径，其中给定的相机像素接收来自投影仪的多个位置的光。在双模式多路径的情况下，相机像素接收来自投影机的恰好两个位置的光，当光线从反射表面或沿着边缘切片通过像素的阶梯边缘反射时出现，使得像素同时看到前景和背景表面。在本文中，我们提出了一个通用的数学模型，并解决相位测量轮廓测量扫描仪中的双模多路径问题，以测量两个光路之间的相长和相消干涉，并利用这个有趣的提示，分离路径，分离深度测量。我们还通过模拟和一些具有挑战性的实际案例验证了我们的算法。

##### URL
[https://arxiv.org/abs/1706.02715](https://arxiv.org/abs/1706.02715)

##### PDF
[https://arxiv.org/pdf/1706.02715](https://arxiv.org/pdf/1706.02715)

