---
layout: post
title: "RayNet: Learning Volumetric 3D Reconstruction with Ray Potentials"
date: 2019-01-06 12:53:18
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Despoina Paschalidou, Ali Osman Ulusoy, Carolin Schmitt, Luc van Gool, Andreas Geiger
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we consider the problem of reconstructing a dense 3D model using images captured from different views. Recent methods based on convolutional neural networks (CNN) allow learning the entire task from data. However, they do not incorporate the physics of image formation such as perspective geometry and occlusion. Instead, classical approaches based on Markov Random Fields (MRF) with ray-potentials explicitly model these physical processes, but they cannot cope with large surface appearance variations across different viewpoints. In this paper, we propose RayNet, which combines the strengths of both frameworks. RayNet integrates a CNN that learns view-invariant feature representations with an MRF that explicitly encodes the physics of perspective projection and occlusion. We train RayNet end-to-end using empirical risk minimization. We thoroughly evaluate our approach on challenging real-world datasets and demonstrate its benefits over a piece-wise trained baseline, hand-crafted models as well as other learning-based approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01535](http://arxiv.org/abs/1901.01535)

##### PDF
[http://arxiv.org/pdf/1901.01535](http://arxiv.org/pdf/1901.01535)

