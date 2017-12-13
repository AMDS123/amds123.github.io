---
layout: post
title: "ZNN - A Fast and Scalable Algorithm for Training 3D Convolutional Networks on Multi-Core and Many-Core Shared Memory Machines"
date: 2015-10-22 18:14:42
categories: arXiv_CV
tags: arXiv_CV CNN
author: Aleksandar Zlateski, Kisuk Lee, H. Sebastian Seung
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional networks (ConvNets) have become a popular approach to computer vision. It is important to accelerate ConvNet training, which is computationally costly. We propose a novel parallel algorithm based on decomposition into a set of tasks, most of which are convolutions or FFTs. Applying Brent's theorem to the task dependency graph implies that linear speedup with the number of processors is attainable within the PRAM model of parallel computation, for wide network architectures. To attain such performance on real shared-memory machines, our algorithm computes convolutions converging on the same node of the network with temporal locality to reduce cache misses, and sums the convergent convolution outputs via an almost wait-free concurrent method to reduce time spent in critical sections. We implement the algorithm with a publicly available software package called ZNN. Benchmarking with multi-core CPUs shows that ZNN can attain speedup roughly equal to the number of physical cores. We also show that ZNN can attain over 90x speedup on a many-core CPU (Xeon Phi Knights Corner). These speedups are achieved for network architectures with widths that are in common use. The task parallelism of the ZNN algorithm is suited to CPUs, while the SIMD parallelism of previous algorithms is compatible with GPUs. Through examples, we show that ZNN can be either faster or slower than certain GPU implementations depending on specifics of the network architecture, kernel sizes, and density and size of the output patch. ZNN may be less costly to develop and maintain, due to the relative ease of general-purpose CPU programming.

##### Abstract (translated by Google)
卷积网络（ConvNet）已经成为计算机视觉的流行方法。加速ConvNet训练是非常重要的，这在计算上是昂贵的。我们提出了一种基于分解成一组任务的新型并行算法，其中大部分是卷积或FFT。将布伦特定理应用于任务依赖图意味着对于宽网络架构，在并行计算的PRAM模型内可以实现具有处理器数量的线性加速。为了在真正的共享内存机器上获得这样的性能，我们的算法计算收敛在网络的同一节点上的卷积，以减少缓存缺失，并且通过几乎等待的并发方法来将收敛的卷积输出相加，以减少花费在关键部分。我们使用一个名为ZNN的公开可用的软件包来实现该算法。使用多核CPU进行基准测试表明，ZNN可以达到大致等于物理内核数量的加速。我们还展示了ZNN可以在多核CPU（Xeon Phi Knights Corner）上实现超过90倍的加速。网络体系结构的这些加速功能是通用的宽度。 ZNN算法的任务并行性适用于CPU，而以前算法的SIMD并行性与GPU兼容。通过举例，我们展示了ZNN可以比某些GPU实现更快或更慢，具体取决于网络体系结构，内核大小，输出补丁的密度和大小。由于通用C​​PU编程相对简单，ZNN的开发和维护成本可能会更低。

##### URL
[https://arxiv.org/abs/1510.06706](https://arxiv.org/abs/1510.06706)

##### PDF
[https://arxiv.org/pdf/1510.06706](https://arxiv.org/pdf/1510.06706)

