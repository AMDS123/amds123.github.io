---
layout: post
title: "Probabilistic Motion Modeling from Medical Image Sequences: Application to Cardiac Cine-MRI"
date: 2019-07-31 14:25:47
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Julian Krebs, Tommaso Mansi, Nicholas Ayache, Herv&#xe9; Delingette
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to learn a probabilistic motion model from a sequence of images. Besides spatio-temporal registration, our method offers to predict motion from a limited number of frames, useful for temporal super-resolution. The model is based on a probabilistic latent space and a novel temporal dropout training scheme. This enables simulation and interpolation of realistic motion patterns given only one or any subset of frames of a sequence. The encoded motion also allows to be transported from one subject to another without the need of inter-subject registration. An unsupervised generative deformation model is applied within a temporal convolutional network which leads to a diffeomorphic motion model, encoded as a low-dimensional motion matrix. Applied to cardiac cine-MRI sequences, we show improved registration accuracy and spatio-temporally smoother deformations compared to three state-of-the-art registration algorithms. Besides, we demonstrate the model's applicability to motion transport by simulating a pathology in a healthy case. Furthermore, we show an improved motion reconstruction from incomplete sequences compared to linear and cubic interpolation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13524](http://arxiv.org/abs/1907.13524)

##### PDF
[http://arxiv.org/pdf/1907.13524](http://arxiv.org/pdf/1907.13524)

