---
layout: post
title: "Fast Fourier Color Constancy"
date: 2017-03-16 22:38:28
categories: arXiv_CV
tags: arXiv_CV
author: Jonathan T. Barron, Yun-Ta Tsai
mathjax: true
---

* content
{:toc}

##### Abstract
We present Fast Fourier Color Constancy (FFCC), a color constancy algorithm which solves illuminant estimation by reducing it to a spatial localization task on a torus. By operating in the frequency domain, FFCC produces lower error rates than the previous state-of-the-art by 13-20% while being 250-3000 times faster. This unconventional approach introduces challenges regarding aliasing, directional statistics, and preconditioning, which we address. By producing a complete posterior distribution over illuminants instead of a single illuminant estimate, FFCC enables better training techniques, an effective temporal smoothing technique, and richer methods for error analysis. Our implementation of FFCC runs at ~700 frames per second on a mobile device, allowing it to be used as an accurate, real-time, temporally-coherent automatic white balance algorithm.

##### Abstract (translated by Google)
我们提出了快速傅里叶色彩恒常（FFCC），一种颜色恒常算法，它通过将其减少到一个环面上的空间定位任务来解决光源估计。通过在频域操作，FFCC产生的错误率比以前的技术水平低13-20％，同时快250-3000倍。这种非常规的方法引入了关于别名，方向统计和预处理的挑战，我们将解决这个问题。通过在光源上产生一个完整的后验分布而不是单一的光源估计，FFCC能够提供更好的训练技术，有效的时间平滑技术和更丰富的误差分析方法。我们在移动设备上以每秒700帧的速度运行FFCC，可以将其用作精确的实时时间相干自动白平衡算法。

##### URL
[https://arxiv.org/abs/1611.07596](https://arxiv.org/abs/1611.07596)

##### PDF
[https://arxiv.org/pdf/1611.07596](https://arxiv.org/pdf/1611.07596)

