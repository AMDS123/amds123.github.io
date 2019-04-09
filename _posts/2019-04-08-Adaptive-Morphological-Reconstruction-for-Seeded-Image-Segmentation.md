---
layout: post
title: "Adaptive Morphological Reconstruction for Seeded Image Segmentation"
date: 2019-04-08 11:56:07
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Tao Lei, Xiaohong Jia, Tongliang Liu, Shigang Liu, Hongying Meng, Asoke K. Nandi
mathjax: true
---

* content
{:toc}

##### Abstract
Morphological reconstruction (MR) is often employed by seeded image segmentation algorithms such as watershed transform and power watershed as it is able to filter seeds (regional minima) to reduce over-segmentation. However, MR might mistakenly filter meaningful seeds that are required for generating accurate segmentation and it is also sensitive to the scale because a single-scale structuring element is employed. In this paper, a novel adaptive morphological reconstruction (AMR) operation is proposed that has three advantages. Firstly, AMR can adaptively filter useless seeds while preserving meaningful ones. Secondly, AMR is insensitive to the scale of structuring elements because multiscale structuring elements are employed. Finally, AMR has two attractive properties: monotonic increasingness and convergence that help seeded segmentation algorithms to achieve a hierarchical segmentation. Experiments clearly demonstrate that AMR is useful for improving algorithms of seeded image segmentation and seed-based spectral segmentation. Compared to several state-of-the-art algorithms, the proposed algorithms provide better segmentation results requiring less computing time. Source code is available at https://github.com/SUST-reynole/AMR.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03973](http://arxiv.org/abs/1904.03973)

##### PDF
[http://arxiv.org/pdf/1904.03973](http://arxiv.org/pdf/1904.03973)

