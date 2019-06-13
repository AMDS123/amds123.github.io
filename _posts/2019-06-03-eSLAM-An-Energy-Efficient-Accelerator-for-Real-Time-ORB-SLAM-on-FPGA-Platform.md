---
layout: post
title: "eSLAM: An Energy-Efficient Accelerator for Real-Time ORB-SLAM on FPGA Platform"
date: 2019-06-03 16:30:06
categories: arXiv_CV
tags: arXiv_CV Optimization SLAM
author: Runze Liu, Jianlei Yang, Yiran Chen, Weisheng Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Simultaneous Localization and Mapping (SLAM) is a critical task for autonomous navigation. However, due to the computational complexity of SLAM algorithms, it is very difficult to achieve real-time implementation on low-power platforms.We propose an energy efficient architecture for real-time ORB (Oriented-FAST and Rotated- BRIEF) based visual SLAM system by accelerating the most time consuming stages of feature extraction and matching on FPGA platform.Moreover, the original ORB descriptor pattern is reformed as a rotational symmetric manner which is much more hardware friendly. Optimizations including rescheduling and parallelizing are further utilized to improve the throughput and reduce the memory footprint. Compared with Intel i7 and ARM Cortex-A9 CPUs on TUM dataset, our FPGA realization achieves up to 3X and 31X frame rate improvement, as well as up to 71X and 25X energy efficiency improvement, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.05096](http://arxiv.org/abs/1906.05096)

##### PDF
[http://arxiv.org/pdf/1906.05096](http://arxiv.org/pdf/1906.05096)

