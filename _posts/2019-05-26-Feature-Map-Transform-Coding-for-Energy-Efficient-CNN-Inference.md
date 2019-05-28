---
layout: post
title: "Feature Map Transform Coding for Energy-Efficient CNN Inference"
date: 2019-05-26 16:29:47
categories: arXiv_CV
tags: arXiv_CV CNN Inference Relation
author: Brian Chmiel, Chaim Baskin, Ron Banner, Evgenii Zheltonozhskii, Yevgeny Yermolin, Alex Karbachevsky, Alex M. Bronstein, Avi Mendelson
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) achieve state-of-the-art accuracy in a variety of tasks in computer vision and beyond. One of the major obstacles hindering the ubiquitous use of CNNs for inference on low-power edge devices is their relatively high computational complexity and memory bandwidth requirements. The latter often dominates the energy footprint on modern hardware. In this paper, we introduce a lossy transform coding approach, inspired by image and video compression, designed to reduce the memory bandwidth due to the storage of intermediate activation calculation results. Our method exploits the high correlations between feature maps and adjacent pixels and allows to halve the data transfer volumes to the main memory without re-training. We analyze the performance of our approach on a variety of CNN architectures and demonstrated FPGA implementation of ResNet18 with our approach results in reduction of around 40% in the memory energy footprint compared to quantized network with negligible impact on accuracy. A reference implementation is available at https://github.com/CompressTeam/TransformCodingInference

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10830](http://arxiv.org/abs/1905.10830)

##### PDF
[http://arxiv.org/pdf/1905.10830](http://arxiv.org/pdf/1905.10830)

