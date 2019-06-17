---
layout: post
title: "MonoLoco: Monocular 3D Pedestrian Localization and Uncertainty Estimation"
date: 2019-06-14 07:39:03
categories: arXiv_CV
tags: arXiv_CV
author: Lorenzo Bertoni, Sven Kreiss, Alexandre Alahi
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the fundamentally ill-posed problem of 3D human localization from monocular RGB images. Driven by the limitation of neural networks outputting point estimates, we address the ambiguity in the task with a new neural network predicting confidence intervals through a loss function based on the Laplace distribution. Our architecture is a light-weight feed-forward neural network which predicts the 3D coordinates given 2D human pose. The design is particularly well suited for small training data and cross-dataset generalization. Our experiments show that (i) we outperform state-of-the art results on KITTI and nuScenes datasets, (ii) even outperform stereo for far-away pedestrians, and (iii) estimate meaningful confidence intervals. We further share insights on our model of uncertainty in case of limited observation and out-of-distribution samples.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.06059](https://arxiv.org/abs/1906.06059)

##### PDF
[https://arxiv.org/pdf/1906.06059](https://arxiv.org/pdf/1906.06059)

