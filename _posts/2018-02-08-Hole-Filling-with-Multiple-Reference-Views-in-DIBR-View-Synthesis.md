---
layout: post
title: "Hole Filling with Multiple Reference Views in DIBR View Synthesis"
date: 2018-02-08 23:38:12
categories: arXiv_CV
tags: arXiv_CV
author: Shuai Li, Ce Zhu, Ming-Ting Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Depth-image-based rendering (DIBR) oriented view synthesis has been widely employed in the current depth-based 3D video systems by synthesizing a virtual view from an arbitrary viewpoint. However, holes may appear in the synthesized view due to disocclusion, thus significantly degrading the quality. Consequently, efforts have been made on developing effective and efficient hole filling algorithms. Current hole filling techniques generally extrapolate/interpolate the hole regions with the neighboring information based on an assumption that the texture pattern in the holes is similar to that of the neighboring background information. However, in many scenarios especially of complex texture, the assumption may not hold. In other words, hole filling techniques can only provide an estimation for a hole which may not be good enough or may even be erroneous considering a wide variety of complex scene of images. In this paper, we first examine the view interpolation with multiple reference views, demonstrating that the problem of emerging holes in a target virtual view can be greatly alleviated by making good use of other neighboring complementary views in addition to its two (commonly used) most neighboring primary views. The effects of using multiple views for view extrapolation in reducing holes are also investigated in this paper. In view of the 3D Video and ongoing free-viewpoint TV standardization, we propose a new view synthesis framework which employs multiple views to synthesize output virtual views. Furthermore, a scheme of selective warping of complementary views is developed by efficiently locating a small number of useful pixels in the complementary views for hole reduction, to avoid a full warping of additional complementary views thus lowering greatly the warping complexity.

##### Abstract (translated by Google)
基于深度图像的渲染（DIBR）的视图合成已经被广泛用于当前基于深度的3D视频系统中，通过从任意视点合成虚拟视图。但是，由于断层现象，合成视图中可能会出现空洞，从而显着降低质量。因此，已经努力开发有效和高效的孔填充算法。目前的孔填充技术通常基于孔中的纹理图案与相邻背景信息的孔洞纹理图案类似的假设，利用相邻信息来外插/内插孔区域。但是，在许多情况下，特别是复杂的纹理，假设可能不成立。换句话说，考虑到各种各样复杂的图像场景，洞填充技术只能提供一个洞可能不够好甚至是错误的估计。在本文中，我们首先研究具有多个参考视图的视图插值，这证明了除了其两个（常用的）大部分之外，还可以充分利用其他相邻的互补视图来大大缓解目标虚拟视图中出现的孔的问题相邻的主要观点。本文还研究了使用多视图进行视图外插减少孔洞的影响。鉴于三维视频和正在进行的自由视点电视标准化，我们提出了一个新的视图综合框架，采用多视图合成输出的虚拟视图。此外，通过有效地定位互补视图中的少量有用像素以减少孔，从而开发了互补视图的选择性变形的方案，以避免附加互补视图的完全变形，从而大大降低了变形复杂度。

##### URL
[http://arxiv.org/abs/1802.03079](http://arxiv.org/abs/1802.03079)

##### PDF
[http://arxiv.org/pdf/1802.03079](http://arxiv.org/pdf/1802.03079)

