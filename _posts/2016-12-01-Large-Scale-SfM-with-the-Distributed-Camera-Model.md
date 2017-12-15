---
layout: post
title: "Large Scale SfM with the Distributed Camera Model"
date: 2016-12-01 02:09:31
categories: arXiv_CV
tags: arXiv_CV
author: Chris Sweeney, Victor Fragoso, Tobias Hollerer, Matthew Turk
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the distributed camera model, a novel model for Structure-from-Motion (SfM). This model describes image observations in terms of light rays with ray origins and directions rather than pixels. As such, the proposed model is capable of describing a single camera or multiple cameras simultaneously as the collection of all light rays observed. We show how the distributed camera model is a generalization of the standard camera model and describe a general formulation and solution to the absolute camera pose problem that works for standard or distributed cameras. The proposed method computes a solution that is up to 8 times more efficient and robust to rotation singularities in comparison with gDLS. Finally, this method is used in an novel large-scale incremental SfM pipeline where distributed cameras are accurately and robustly merged together. This pipeline is a direct generalization of traditional incremental SfM; however, instead of incrementally adding one camera at a time to grow the reconstruction the reconstruction is grown by adding a distributed camera. Our pipeline produces highly accurate reconstructions efficiently by avoiding the need for many bundle adjustment iterations and is capable of computing a 3D model of Rome from over 15,000 images in just 22 minutes.

##### Abstract (translated by Google)
我们介绍分布式摄像机模型，一种新型的运动结构（SfM）模型。这个模型描述了用射线的起源和方向而不是像素的光线的图像观察。因此，所提出的模型能够在观察到所有光线的集合的同时描述单个相机或多个相机。我们展示了分布式摄像机模型是如何推广标准摄像机模型的，并描述了适用于标准或分布式摄像机的绝对摄像机姿态问题的一般公式和解决方案。与gDLS相比，所提出的方法计算的解决方案效率高达8倍，并且对于旋转奇异性具有鲁棒性。最后，这种方法被用于一个新颖的大规模增量SfM管道，其中分布式摄像机被精确和稳健地合并在一起。该管道是传统增量式SfM的直接推广;然而，不是一次增加一个摄像机来增加重建，而是通过增加分布式摄像机来增加重建。我们的流水线通过避免需要多次束调整迭代而有效地产生高度精确的重建，并且能够在22分钟内从超过15,000个图像计算罗马的3D模型。

##### URL
[https://arxiv.org/abs/1607.03949](https://arxiv.org/abs/1607.03949)

##### PDF
[https://arxiv.org/pdf/1607.03949](https://arxiv.org/pdf/1607.03949)

