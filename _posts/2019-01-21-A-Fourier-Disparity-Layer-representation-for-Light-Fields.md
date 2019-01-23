---
layout: post
title: "A Fourier Disparity Layer representation for Light Fields"
date: 2019-01-21 13:11:11
categories: arXiv_CV
tags: arXiv_CV Gradient_Descent
author: Mikael Le Pendu, Christine Guillemot, Aljosa Smolic
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a new Light Field representation for efficient Light Field processing and rendering called Fourier Disparity Layers (FDL). The proposed FDL representation samples the Light Field in the depth (or equivalently the disparity) dimension by decomposing the scene as a discrete sum of layers. The layers can be constructed from various types of Light Field inputs including a set of sub-aperture images, a focal stack, or even a combination of both. From our derivations in the Fourier domain, the layers are simply obtained by a regularized least square regression performed independently at each spatial frequency, which is efficiently parallelized in a GPU implementation. Our model is also used to derive a gradient descent based calibration step that estimates the input view positions and an optimal set of disparity values required for the layer construction. Once the layers are known, they can be simply shifted and filtered to produce different viewpoints of the scene while controlling the focus and simulating a camera aperture of arbitrary shape and size. Our implementation in the Fourier domain allows real time Light Field rendering. Finally, direct applications such as view interpolation or extrapolation and denoising are presented and evaluated.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06919](http://arxiv.org/abs/1901.06919)

##### PDF
[http://arxiv.org/pdf/1901.06919](http://arxiv.org/pdf/1901.06919)

