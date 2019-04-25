---
layout: post
title: "Chunkflow: Distributed Hybrid Cloud Processing of Large 3D Images by Convolutional Nets"
date: 2019-04-23 18:47:57
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Jingpeng Wu (1), William M. Silversmith (1), H. Sebastian Seung (1 and 2) ((1) Princeton Neuroscience Institute, Princeton University, (2) Department of Computer Science, Princeton University)
mathjax: true
---

* content
{:toc}

##### Abstract
It is now common to process volumetric biomedical images using 3D Convolutional Networks (ConvNets). This can be challenging for the teravoxel and even petavoxel images that are being acquired today by light or electron microscopy. Here we introduce chunkflow, a software framework for distributing ConvNet processing over local and cloud GPUs and CPUs. The image volume is divided into overlapping chunks, each chunk is processed by a ConvNet, and the results are blended together to yield the output image. The frontend submits ConvNet tasks to a cloud queue. The tasks are executed by local and cloud GPUs and CPUs. Thanks to the fault-tolerant architecture of Chunkflow, cost can be greatly reduced by utilizing cheap unstable cloud instances. Chunkflow currently supports PyTorch for GPUs and PZnet for CPUs. To illustrate its usage, a large 3D brain image from serial section electron microscopy was processed by a 3D ConvNet with a U-Net style architecture. Chunkflow provides some chunk operations for general use, and the operations can be composed flexibly in a command line interface.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10489](http://arxiv.org/abs/1904.10489)

##### PDF
[http://arxiv.org/pdf/1904.10489](http://arxiv.org/pdf/1904.10489)

