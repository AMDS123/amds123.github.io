---
layout: post
title: "HDM-Net: Monocular Non-Rigid 3D Reconstruction with Learned Deformation Model"
date: 2019-08-05 18:56:15
categories: arXiv_CV
tags: arXiv_CV Face Tracking
author: Vladislav Golyanik, Soshi Shimada, Kiran Varanasi, Didier Stricker
mathjax: true
---

* content
{:toc}

##### Abstract
Monocular dense 3D reconstruction of deformable objects is a hard ill-posed problem in computer vision. Current techniques either require dense correspondences and rely on motion and deformation cues, or assume a highly accurate reconstruction (referred to as a template) of at least a single frame given in advance and operate in the manner of non-rigid tracking. Accurate computation of dense point tracks often requires multiple frames and might be computationally expensive. Availability of a template is a very strong prior which restricts system operation to a pre-defined environment and scenarios. In this work, we propose a new hybrid approach for monocular non-rigid reconstruction which we call Hybrid Deformation Model Network (HDM-Net). In our approach, deformation model is learned by a deep neural network, with a combination of domain-specific loss functions. We train the network with multiple states of a non-rigidly deforming structure with a known shape at rest. HDM-Net learns different reconstruction cues including texture-dependent surface deformations, shading and contours. We show generalisability of HDM-Net to states not presented in the training dataset, with unseen textures and under new illumination conditions. Experiments with noisy data and a comparison with other methods demonstrate robustness and accuracy of the proposed approach and suggest possible application scenarios of the new technique in interventional diagnostics and augmented reality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.10193](http://arxiv.org/abs/1803.10193)

##### PDF
[http://arxiv.org/pdf/1803.10193](http://arxiv.org/pdf/1803.10193)

