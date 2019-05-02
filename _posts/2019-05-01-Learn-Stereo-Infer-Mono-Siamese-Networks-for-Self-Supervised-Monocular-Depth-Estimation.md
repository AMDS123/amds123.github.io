---
layout: post
title: "Learn Stereo, Infer Mono: Siamese Networks for Self-Supervised, Monocular, Depth Estimation"
date: 2019-05-01 17:36:19
categories: arXiv_CV
tags: arXiv_CV
author: Matan Goldman, Tal Hassner, Shai Avidan
mathjax: true
---

* content
{:toc}

##### Abstract
The field of self-supervised monocular depth estimation has seen huge advancements in recent years. Most methods assume stereo data is available during training but usually under-utilize it and only treat it as a reference signal. We propose a novel self-supervised approach which uses both left and right images equally during training, but can still be used with a single input image at test time, for monocular depth estimation. Our Siamese network architecture consists of two, twin networks, each learns to predict a disparity map from a single image. At test time, however, only one of these networks is used in order to infer depth. We show state-of-the-art results on the standard KITTI Eigen split benchmark as well as being the highest scoring self-supervised method on the new KITTI single view benchmark. To demonstrate the ability of our method to generalize to new data sets, we further provide results on the Make3D benchmark, which was not used during training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00401](http://arxiv.org/abs/1905.00401)

##### PDF
[http://arxiv.org/pdf/1905.00401](http://arxiv.org/pdf/1905.00401)

