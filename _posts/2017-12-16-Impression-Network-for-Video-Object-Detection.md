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
Video object detection is more challenging compared to image object detection. Previous works proved that applying object detector frame by frame is not only slow but also inaccurate. Visual clues get weakened by defocus and motion blur, causing failure on corresponding frames. Multi-frame feature fusion methods proved effective in improving the accuracy, but they dramatically sacrifice the speed. Feature propagation based methods proved effective in improving the speed, but they sacrifice the accuracy. So is it possible to improve speed and performance simultaneously? Inspired by how human utilize impression to recognize objects from blurry frames, we propose Impression Network that embodies a natural and efficient feature aggregation mechanism. In our framework, an impression feature is established by iteratively absorbing sparsely extracted frame features. The impression feature is propagated all the way down the video, helping enhance features of low-quality frames. This impression mechanism makes it possible to perform long-range multi-frame feature fusion among sparse keyframes with minimal overhead. It significantly improves per-frame detection baseline on ImageNet VID while being 3 times faster (20 fps). We hope Impression Network can provide a new perspective on video feature enhancement. Code will be made available.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1712.05896](https://arxiv.org/abs/1712.05896)

##### PDF
[https://arxiv.org/pdf/1712.05896](https://arxiv.org/pdf/1712.05896)

