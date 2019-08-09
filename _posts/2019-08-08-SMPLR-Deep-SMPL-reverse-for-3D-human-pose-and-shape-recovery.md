---
layout: post
title: "SMPLR: Deep SMPL reverse for 3D human pose and shape recovery"
date: 2019-08-08 10:56:36
categories: arXiv_CV
tags: arXiv_CV Regularization Prediction
author: Meysam Madadi, Hugo Bertiche, Sergio Escalera
mathjax: true
---

* content
{:toc}

##### Abstract
Current state-of-the-art in 3D human pose and shape recovery relies on deep neural networks and statistical morphable body models, such as the Skinned Multi-Person Linear model (SMPL). However, regardless of the advantages of having both body pose and shape, SMPL-based solutions have shown difficulties to predict 3D bodies accurately. This is mainly due to the unconstrained nature of SMPL, which may generate unrealistic body meshes. Because of this, regression of SMPL parameters is a difficult task, often addressed with complex regularization terms. In this paper we propose to embed SMPL within a deep model to accurately estimate 3D pose and shape from a still RGB image. We use CNN-based 3D joint predictions as an intermediate representation to regress SMPL pose and shape parameters. Later, 3D joints are reconstructed again in the SMPL output. This module can be seen as an autoencoder where the encoder is a deep neural network and the decoder is SMPL model. We refer to this as SMPL reverse (SMPLR). By implementing SMPLR as an encoder-decoder we avoid the need of complex constraints on pose and shape. Furthermore, given that in-the-wild datasets usually lack accurate 3D annotations, it is desirable to lift 2D joints to 3D without pairing 3D annotations with RGB images. Therefore, we also propose a denoising autoencoder (DAE) module between CNN and SMPLR, able to lift 2D joints to 3D and partially recover from structured error. We evaluate our method on SURREAL and Human3.6M datasets, showing improvement over SMPL-based state-of-the-art alternatives by about 4 and 25 millimeters, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10766](http://arxiv.org/abs/1812.10766)

##### PDF
[http://arxiv.org/pdf/1812.10766](http://arxiv.org/pdf/1812.10766)

