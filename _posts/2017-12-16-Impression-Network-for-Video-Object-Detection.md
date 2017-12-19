---
layout: post
title: "Impression Network for Video Object Detection"
date: 2017-12-16 02:53:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Detection
author: Congrui Hetang, Hongwei Qin, Shaohui Liu, Junjie Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Video object detection is more challenging compared to image object detection. Previous works proved that applying object detector frame by frame is not only slow but also inaccurate. Visual clues get weakened by defocus and motion blur, causing failure on corresponding frames. Multi-frame feature fusion methods proved effective in improving the accuracy, but they dramatically sacrifice the speed. Feature propagation based methods proved effective in improving the speed, but they sacrifice the accuracy. So is it possible to improve speed and performance simultaneously? 
 Inspired by how human utilize impression to recognize objects from blurry frames, we propose Impression Network that embodies a natural and efficient feature aggregation mechanism. In our framework, an impression feature is established by iteratively absorbing sparsely extracted frame features. The impression feature is propagated all the way down the video, helping enhance features of low-quality frames. This impression mechanism makes it possible to perform long-range multi-frame feature fusion among sparse keyframes with minimal overhead. It significantly improves per-frame detection baseline on ImageNet VID while being 3 times faster (20 fps). We hope Impression Network can provide a new perspective on video feature enhancement. Code will be made available.

##### Abstract (translated by Google)
与图像对象检测相比，视频对象检测更具挑战性。以前的工作证明，逐帧应用目标检测器不但速度慢，而且不准确。视觉线索由于散焦和运动模糊而变弱，导致相应帧的失败。多帧特征融合方法在提高精度方面证明是有效的，但是它们显着地牺牲了速度。基于特征传播的方法被证明在提高速度方面是有效的，但是它们牺牲了准确性。那么是否可以同时提高速度和性能呢？
 受到人们如何利用印象识别模糊框架中的物体的启发，我们提出了体现自然和高效的特征聚合机制的印象网络。在我们的框架中，通过迭代吸收稀疏提取的帧特征来建立印象特征。展示功能一直沿着视频传播，有助于增强低质量帧的功能。这种印象机制使得能够以最小的开销在稀疏关键帧之间执行远距离多帧特征融合。它显着提高了ImageNet VID的每帧检测基线，同时提高了3倍（20 fps）。我们希望印象网络能够提供视频特性增强的新视角。代码将被提供。

##### URL
[http://arxiv.org/abs/1712.05896](http://arxiv.org/abs/1712.05896)

##### PDF
[http://arxiv.org/pdf/1712.05896](http://arxiv.org/pdf/1712.05896)

