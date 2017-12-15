---
layout: post
title: "FAST: A Framework to Accelerate Super-Resolution Processing on Compressed Videos"
date: 2017-08-04 18:20:25
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Relation
author: Zhengdong Zhang, Vivienne Sze
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art super-resolution (SR) algorithms require significant computational resources to achieve real-time throughput (e.g., 60Mpixels/s for HD video). This paper introduces FAST (Free Adaptive Super-resolution via Transfer), a framework to accelerate any SR algorithm applied to compressed videos. FAST exploits the temporal correlation between adjacent frames such that SR is only applied to a subset of frames; SR pixels are then transferred to the other frames. The transferring process has negligible computation cost as it uses information already embedded in the compressed video (e.g., motion vectors and residual). Adaptive processing is used to retain accuracy when the temporal correlation is not present (e.g., occlusions). FAST accelerates state-of-the-art SR algorithms by up to 15x with a visual quality loss of 0.2dB. FAST is an important step towards real-time SR algorithms for ultra-HD displays and energy constrained devices (e.g., phones and tablets).

##### Abstract (translated by Google)
最先进的超分辨率（SR）算法需要大量的计算资源来实现实时吞吐量（例如，高清视频的60M像素/秒）。本文介绍了FAST（自适应超分辨率通过传输），一个框架加速任何SR算法应用于压缩视频。 FAST利用相邻帧之间的时间相关性，使得SR仅被应用于帧的子集; SR像素然后被转移到其他帧。由于传输过程使用已经嵌入在压缩视频中的信息（例如，运动矢量和残差），所以传输过程具有可忽略的计算成本。当不存在时间相关性（例如，遮挡）时，使用自适应处理来保持准确性。 FAST将最先进的SR算法加速达15倍，视觉质量损失为0.2dB。 FAST是超高清显示器和能源受限设备（如手机和平板电脑）的实时SR算法的重要一步。

##### URL
[https://arxiv.org/abs/1603.08968](https://arxiv.org/abs/1603.08968)

##### PDF
[https://arxiv.org/pdf/1603.08968](https://arxiv.org/pdf/1603.08968)

