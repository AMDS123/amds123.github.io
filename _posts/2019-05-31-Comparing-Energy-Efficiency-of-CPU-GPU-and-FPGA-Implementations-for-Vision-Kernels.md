---
layout: post
title: "Comparing Energy Efficiency of CPU, GPU and FPGA Implementations for Vision Kernels"
date: 2019-05-31 21:25:42
categories: arXiv_CV
tags: arXiv_CV
author: Murad Qasaimeh, Kristof Denolf, Jack Lo, Kees Vissers, Joseph Zambreno, Phillip H. Jones
mathjax: true
---

* content
{:toc}

##### Abstract
Developing high performance embedded vision applications requires balancing run-time performance with energy constraints. Given the mix of hardware accelerators that exist for embedded computer vision (e.g. multi-core CPUs, GPUs, and FPGAs), and their associated vendor optimized vision libraries, it becomes a challenge for developers to navigate this fragmented solution space. To aid with determining which embedded platform is most suitable for their application, we conduct a comprehensive benchmark of the run-time performance and energy efficiency of a wide range of vision kernels. We discuss rationales for why a given underlying hardware architecture innately performs well or poorly based on the characteristics of a range of vision kernel categories. Specifically, our study is performed for three commonly used HW accelerators for embedded vision applications: ARM57 CPU, Jetson TX2 GPU and ZCU102 FPGA, using their vendor optimized vision libraries: OpenCV, VisionWorks and xfOpenCV. Our results show that the GPU achieves an energy/frame reduction ratio of 1.1-3.2x compared to the others for simple kernels. While for more complicated kernels and complete vision pipelines, the FPGA outperforms the others with energy/frame reduction ratios of 1.2-22.3x. It is also observed that the FPGA performs increasingly better as a vision application's pipeline complexity grows.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11879](http://arxiv.org/abs/1906.11879)

##### PDF
[http://arxiv.org/pdf/1906.11879](http://arxiv.org/pdf/1906.11879)

