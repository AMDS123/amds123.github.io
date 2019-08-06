---
layout: post
title: "Adversarial View-Consistent Learning for Monocular Depth Estimation"
date: 2019-08-04 09:37:24
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Yixuan Liu, Yuwang Wang, Shengjin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of Monocular Depth Estimation (MDE). Existing approaches on MDE usually model it as a pixel-level regression problem, ignoring the underlying geometry property. We empirically find this may result in sub-optimal solution: while the predicted depth map presents small loss value in one specific view, it may exhibit large loss if viewed in different directions. In this paper, inspired by multi-view stereo (MVS), we propose an Adversarial View-Consistent Learning (AVCL) framework to force the estimated depth map to be all reasonable viewed from multiple views. To this end, we first design a differentiable depth map warping operation, which is end-to-end trainable, and then propose a pose generator to generate novel views for a given image in an adversarial manner. Collaborating with the differentiable depth map warping operation, the pose generator encourages the depth estimation network to learn from hard views, hence produce view-consistent depth maps . We evaluate our method on NYU Depth V2 dataset and the experimental results show promising performance gain upon state-of-the-art MDE approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01301](http://arxiv.org/abs/1908.01301)

##### PDF
[http://arxiv.org/pdf/1908.01301](http://arxiv.org/pdf/1908.01301)

