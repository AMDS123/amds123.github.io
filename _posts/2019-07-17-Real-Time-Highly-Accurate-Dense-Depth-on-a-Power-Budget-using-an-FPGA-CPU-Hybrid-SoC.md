---
layout: post
title: "Real-Time Highly Accurate Dense Depth on a Power Budget using an FPGA-CPU Hybrid SoC"
date: 2019-07-17 20:22:47
categories: arXiv_CV
tags: arXiv_CV
author: Oscar Rahnama, Tommaso Cavallari, Stuart Golodetz, Alessio Tonioni, Thomas Joy, Luigi Di Stefano, Simon Walker, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Obtaining highly accurate depth from stereo images in real time has many applications across computer vision and robotics, but in some contexts, upper bounds on power consumption constrain the feasible hardware to embedded platforms such as FPGAs. Whilst various stereo algorithms have been deployed on these platforms, usually cut down to better match the embedded architecture, certain key parts of the more advanced algorithms, e.g. those that rely on unpredictable access to memory or are highly iterative in nature, are difficult to deploy efficiently on FPGAs, and thus the depth quality that can be achieved is limited. In this paper, we leverage a FPGA-CPU chip to propose a novel, sophisticated, stereo approach that combines the best features of SGM and ELAS-based methods to compute highly accurate dense depth in real time. Our approach achieves an 8.7% error rate on the challenging KITTI 2015 dataset at over 50 FPS, with a power consumption of only 5W.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07745](http://arxiv.org/abs/1907.07745)

##### PDF
[http://arxiv.org/pdf/1907.07745](http://arxiv.org/pdf/1907.07745)

