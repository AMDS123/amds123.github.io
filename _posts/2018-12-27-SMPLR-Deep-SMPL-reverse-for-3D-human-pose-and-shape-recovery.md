---
layout: post
title: "SMPLR: Deep SMPL reverse for 3D human pose and shape recovery"
date: 2018-12-27 16:47:11
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Prediction
author: Meysam Madadi, Hugo Bertiche, Sergio Escalera
mathjax: true
---

* content
{:toc}

##### Abstract
A recent trend in 3D human pose and shape estimation is to use deep learning and statistical morphable body models, such as the parametric Skinned Multi-Person Linear Model (SMPL). However, regardless of the advances in having both body pose and shape, SMPL-based solutions have shown difficulties on achieving accurate predictions. This is due to the unconstrained nature of SMPL, which allows unrealistic poses and shapes, hindering its direct regression or application on the training of deep models. In this paper we propose to embed SMPL within a deep model to efficiently estimate 3D pose and shape from a still RGB image. We use 3D joints as an intermediate representation to regress SMPL parameters which are again recovered as SMPL output. This module can be seen as an autoencoder where encoder is modeled by deep neural networks and decoder is modeled by SMPL. We refer to this procedure as SMPL reverse (SMPLR). Then, input 3D joints can be estimated by any convolutional neural network (CNN). To handle input noise to SMPLR, we propose a denoising autoencoder between CNN and SMPLR which is able to recover structured error. We evaluate our method on SURREAL and Human3.6M datasets showing significant improvement over SMPL-based state-of-the-art alternatives.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10766](http://arxiv.org/abs/1812.10766)

##### PDF
[http://arxiv.org/pdf/1812.10766](http://arxiv.org/pdf/1812.10766)

