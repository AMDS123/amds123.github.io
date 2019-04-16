---
layout: post
title: "A Scalable Near-Memory Architecture for Training Deep Neural Networks on Large In-Memory Datasets"
date: 2018-10-17 10:25:49
categories: arXiv_CV
tags: arXiv_CV Attention CNN Inference
author: Fabian Schuiki, Michael Schaffner, Frank K. Gürkaynak, Luca Benini
mathjax: true
---

* content
{:toc}

##### Abstract
Most investigations into near-memory hardware accelerators for deep neural networks have primarily focused on inference, while the potential of accelerating training has received relatively little attention so far. Based on an in-depth analysis of the key computational patterns in state-of-the-art gradient-based training methods, we propose an efficient near-memory acceleration engine called NTX that can be used to train state-of-the-art deep convolutional neural networks at scale. Our main contributions are: (i) a loose coupling of RISC-V cores and NTX co-processors reducing offloading overhead by 7x over previously published results; (ii) an optimized IEEE754 compliant data path for fast high-precision convolutions and gradient propagation; (iii) evaluation of near-memory computing with NTX embedded into residual area on the Logic Base die of a Hybrid Memory Cube; and (iv) a scaling analysis to meshes of HMCs in a data center scenario. We demonstrate a 2.7x energy efficiency improvement of NTX over contemporary GPUs at 4.4x less silicon area, and a compute performance of 1.2 Tflop/s for training large state-of-the-art networks with full floating-point precision. At the data center scale, a mesh of NTX achieves above 95% parallel and energy efficiency, while providing 2.1x energy savings or 3.1x performance improvement over a GPU-based system.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.04783](https://arxiv.org/abs/1803.04783)

##### PDF
[https://arxiv.org/pdf/1803.04783](https://arxiv.org/pdf/1803.04783)

