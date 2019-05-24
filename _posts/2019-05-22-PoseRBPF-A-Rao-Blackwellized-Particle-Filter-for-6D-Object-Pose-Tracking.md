---
layout: post
title: "PoseRBPF: A Rao-Blackwellized Particle Filter for 6D Object Pose Tracking"
date: 2019-05-22 18:01:55
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking Embedding
author: Xinke Deng, Arsalan Mousavian, Yu Xiang, Fei Xia, Timothy Bretl, Dieter Fox
mathjax: true
---

* content
{:toc}

##### Abstract
Tracking 6D poses of objects from videos provides rich information to a robot in performing different tasks such as manipulation and navigation. In this work, we formulate the 6D object pose tracking problem in the Rao-Blackwellized particle filtering framework, where the 3D rotation and the 3D translation of an object are decoupled. This factorization allows our approach, called PoseRBPF, to efficiently estimate the 3D translation of an object along with the full distribution over the 3D rotation. This is achieved by discretizing the rotation space in a fine-grained manner, and training an auto-encoder network to construct a codebook of feature embeddings for the discretized rotations. As a result, PoseRBPF can track objects with arbitrary symmetries while still maintaining adequate posterior distributions. Our approach achieves state-of-the-art results on two 6D pose estimation benchmarks. A video showing the experiments can be found at https://youtu.be/lE5gjzRKWuA

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09304](http://arxiv.org/abs/1905.09304)

##### PDF
[http://arxiv.org/pdf/1905.09304](http://arxiv.org/pdf/1905.09304)

