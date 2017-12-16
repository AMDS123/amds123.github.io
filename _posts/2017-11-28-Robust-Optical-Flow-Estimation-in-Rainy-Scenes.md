---
layout: post
title: "Robust Optical Flow Estimation in Rainy Scenes"
date: 2017-11-28 15:39:08
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Ruoteng Li, Robby T. Tan, Loong-Fah Cheong
mathjax: true
---

* content
{:toc}

##### Abstract
Optical flow estimation in the rainy scenes is challenging due to background degradation introduced by rain streaks and rain accumulation effects in the scene. Rain accumulation effect refers to poor visibility of remote objects due to the intense rainfall. Most existing optical flow methods are erroneous when applied to rain sequences because the conventional brightness constancy constraint (BCC) and gradient constancy constraint (GCC) generally break down in this situation. Based on the observation that the RGB color channels receive raindrop radiance equally, we introduce a residue channel as a new data constraint to reduce the effect of rain streaks. To handle rain accumulation, our method decomposes the image into a piecewise-smooth background layer and a high-frequency detail layer. It also enforces the BCC on the background layer only. Results on both synthetic dataset and real images show that our algorithm outperforms existing methods on different types of rain sequences. To our knowledge, this is the first optical flow method specifically dealing with rain.

##### Abstract (translated by Google)
雨景中的光流估计是具有挑战性的，因为由场景中的雨纹和雨积聚效应引起的背景劣化。雨积聚效应是指由于强降雨导致的远距离物体的能见度较差。大多数现有的光流方法在应用于降雨序列时是错误的，因为在这种情况下，传统的亮度恒定约束（BCC）和梯度恒定约束（GCC）通常被破坏。基于RGB色彩通道均匀接收雨滴辐射的观测，引入了一个残余通道作为新的数据约束，以减少雨痕的影响。为了处理积雨，我们的方法将图像分解成分片平滑的背景层和高频细节层。它也只在背景层上强制执行BCC。综合数据集和实际图像的结果表明，该算法在不同类型的降雨序列上优于现有方法。就我们所知，这是第一个专门处理雨水的光流方法。

##### URL
[https://arxiv.org/abs/1704.05239](https://arxiv.org/abs/1704.05239)

##### PDF
[https://arxiv.org/pdf/1704.05239](https://arxiv.org/pdf/1704.05239)

