---
layout: post
title: "A Motion Free Approach to Dense Depth Estimation in Complex Dynamic Scene"
date: 2019-02-11 09:45:52
categories: arXiv_CV
tags: arXiv_CV Sparse Deep_Learning
author: Suryansh Kumar, Ram Srivatsav Ghorakavi, Yuchao Dai, Hongdong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the recent success in per-frame monocular dense depth estimation of rigid scenes using deep learning methods, they fail to achieve similar success for complex dynamic scenes, such as MPI Sintel \cite{butler2012naturalistic}. Moreover, conventional geometric methods to address this problem using a piece-wise rigid scene model requires a reliable estimation of motion parameters for each local model, which is difficult to obtain and validate. In this work, we show that, given per-pixel optical flow correspondences between two consecutive frames and the sparse depth prior for the reference frame, we can recover the dense depth map for the successive frames without solving for motion parameters. By assigning the locally rigid structure to the piece-wise planar approximation of a dynamic scene which transforms as rigid as possible over frames, we demonstrate that we can bypass the motion estimation step. In essence, our formulation provides a new way to think and recover dense depth map of a complex dynamic scene which is recursive, incremental and motion free in nature and therefore, it can also be integrated with the modern neural network frameworks for large-scale depth-estimation applications. Our proposed method does not make any prior assumption about the rigidity of a dynamic scene, as a result, it is applicable to a wide range of scenarios. Experimental results show that our method can effectively provide the depth for the successive/multiple frames of a dynamic scene without using any motion parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03791](http://arxiv.org/abs/1902.03791)

##### PDF
[http://arxiv.org/pdf/1902.03791](http://arxiv.org/pdf/1902.03791)

