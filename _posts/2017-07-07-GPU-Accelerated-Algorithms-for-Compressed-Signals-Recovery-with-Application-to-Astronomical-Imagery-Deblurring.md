---
layout: post
title: "GPU-Accelerated Algorithms for Compressed Signals Recovery with Application to Astronomical Imagery Deblurring"
date: 2017-07-07 15:55:28
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Attilio Fiandrotti, Sophie M. Fosson, Chiara Ravazzi, Enrico Magli
mathjax: true
---

* content
{:toc}

##### Abstract
Compressive sensing promises to enable bandwidth-efficient on-board compression of astronomical data by lifting the encoding complexity from the source to the receiver. The signal is recovered off-line, exploiting GPUs parallel computation capabilities to speedup the reconstruction process. However, inherent GPU hardware constraints limit the size of the recoverable signal and the speedup practically achievable. In this work, we design parallel algorithms that exploit the properties of circulant matrices for efficient GPU-accelerated sparse signals recovery. Our approach reduces the memory requirements, allowing us to recover very large signals with limited memory. In addition, it achieves a tenfold signal recovery speedup thanks to ad-hoc parallelization of matrix-vector multiplications and matrix inversions. Finally, we practically demonstrate our algorithms in a typical application of circulant matrices: deblurring a sparse astronomical image in the compressed domain.

##### Abstract (translated by Google)
压缩感测有望通过提高从源到接收机的编码复杂度来实现天文数据的带宽高效的板上压缩。该信号是离线恢复的，利用GPU的并行计算能力来加速重建过程。然而，固有的GPU硬件约束限制了可恢复信号的大小以及实际可实现的加速。在这项工作中，我们设计了并行算法，利用循环矩阵的属性进行高效的GPU加速稀疏信号恢复。我们的方法减少了内存需求，使我们能够利用有限的内存恢复非常大的信号。另外，由于矩阵 - 向量乘法和矩阵求逆的特殊并行化，实现了十倍信号恢复加速。最后，我们在循环矩阵的典型应用中实际演示了我们的算法：在压缩域中去除稀疏天文图像。

##### URL
[https://arxiv.org/abs/1707.02244](https://arxiv.org/abs/1707.02244)

##### PDF
[https://arxiv.org/pdf/1707.02244](https://arxiv.org/pdf/1707.02244)

