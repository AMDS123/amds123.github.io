---
layout: post
title: "ForkNet: Multi-branch Volumetric Semantic Completion from a Single Depth Image"
date: 2019-09-03 12:04:39
categories: arXiv_AI
tags: arXiv_AI Face
author: Yida Wang, David Joseph Tan, Nassir Navab, Federico Tombari
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel model for 3D semantic completion from a single depth image, based on a single encoder and three separate generators used to reconstruct different geometric and semantic representations of the original and completed scene, all sharing the same latent space. To transfer information between the geometric and semantic branches of the network, we introduce paths between them concatenating features at corresponding network layers. Motivated by the limited amount of training samples from real scenes, an interesting attribute of our architecture is the capacity to supplement the existing dataset by generating a new training dataset with high quality, realistic scenes that even includes occlusion and real noise. We build the new dataset by sampling the features directly from latent space which generates a pair of partial volumetric surface and completed volumetric semantic surface. Moreover, we utilize multiple discriminators to increase the accuracy and realism of the reconstructions. We demonstrate the benefits of our approach on standard benchmarks for the two most common completion tasks: semantic 3D scene completion and 3D object completion.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1909.01106](https://arxiv.org/abs/1909.01106)

##### PDF
[https://arxiv.org/pdf/1909.01106](https://arxiv.org/pdf/1909.01106)

