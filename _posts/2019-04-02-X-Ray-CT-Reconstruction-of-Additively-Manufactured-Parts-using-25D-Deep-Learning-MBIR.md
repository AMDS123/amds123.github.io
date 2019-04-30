---
layout: post
title: "X-Ray CT Reconstruction of Additively Manufactured Parts using 2.5D Deep Learning MBIR"
date: 2019-04-02 01:16:29
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Amirkoushyar Ziabari, Michael Kirka, Vincent Paquit, Philip Bingham, Singanallur Venkatakrishnan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a deep learning algorithm to rapidly obtain high quality CT reconstructions for AM parts. In particular, we propose to use CAD models of the parts that are to be manufactured, introduce typical defects and simulate XCT measurements. These simulated measurements were processed using FBP (computationally simple but result in noisy images) and the MBIR technique. We then train a 2.5D deep convolutional neural network [4], deemed 2.5D Deep Learning MBIR (2.5D DL-MBIR), on these pairs of noisy and high-quality 3D volumes to learn a fast, non-linear mapping function. The 2.5D DL-MBIR reconstructs a 3D volume in a 2.5D scheme where each slice is reconstructed from multiple inputs slices of the FBP input. Given this trained system, we can take a small set of measurements on an actual part, process it using a combination of FBP followed by 2.5D DL-MBIR. Both steps can be rapidly performed using GPUs, resulting in a real-time algorithm that achieves the high-quality of MBIR as fast as standard techniques. Intuitively, since CAD models are typically available for parts to be manufactured, this provides a strong constraint "prior" which can be leveraged to improve the reconstruction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12585](http://arxiv.org/abs/1904.12585)

##### PDF
[http://arxiv.org/pdf/1904.12585](http://arxiv.org/pdf/1904.12585)

