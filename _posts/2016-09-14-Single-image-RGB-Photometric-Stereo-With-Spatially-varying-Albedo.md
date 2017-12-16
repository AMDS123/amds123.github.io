---
layout: post
title: "Single-image RGB Photometric Stereo With Spatially-varying Albedo"
date: 2016-09-14 00:39:58
categories: arXiv_CV
tags: arXiv_CV Face
author: Ayan Chakrabarti, Kalyan Sunkavalli
mathjax: true
---

* content
{:toc}

##### Abstract
We present a single-shot system to recover surface geometry of objects with spatially-varying albedos, from images captured under a calibrated RGB photometric stereo setup---with three light directions multiplexed across different color channels in the observed RGB image. Since the problem is ill-posed point-wise, we assume that the albedo map can be modeled as piece-wise constant with a restricted number of distinct albedo values. We show that under ideal conditions, the shape of a non-degenerate local constant albedo surface patch can theoretically be recovered exactly. Moreover, we present a practical and efficient algorithm that uses this model to robustly recover shape from real images. Our method first reasons about shape locally in a dense set of patches in the observed image, producing shape distributions for every patch. These local distributions are then combined to produce a single consistent surface normal map. We demonstrate the efficacy of the approach through experiments on both synthetic renderings as well as real captured images.

##### Abstract (translated by Google)
我们提出了一个单发系统来恢复在一个校准RGB光度立体安装下拍摄的图像的空间变化反照率的物体的表面几何形状---三个光方向在观察到的RGB图像中的不同颜色通道上复用。由于这个问题是不恰当的，所以我们假设反照率地图可以用有限数量的不同反照率值作为分段常数来建模。我们证明，在理想条件下，非退化局部常反照率曲面片的形状理论上可以准确地恢复。此外，我们提出了一个实用和有效的算法，使用这个模型来从实际图像中恢复形状。我们的方法首先在观察图像中的一组密集的斑点中局部形状的原因，为每个斑块产生形状分布。这些局部分布然后被组合以产生单个一致的表面法线贴图。我们通过在合成渲染以及真实捕获的图像上的实验展示了该方法的功效。

##### URL
[https://arxiv.org/abs/1609.04079](https://arxiv.org/abs/1609.04079)

##### PDF
[https://arxiv.org/pdf/1609.04079](https://arxiv.org/pdf/1609.04079)

