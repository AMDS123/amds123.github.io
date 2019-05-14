---
layout: post
title: "Learning to Personalize in Appearance-Based Gaze Tracking"
date: 2019-05-11 10:32:01
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Erik Lind&#xe9;n, Jonas Sj&#xf6;strand, Alexandre Proutiere
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we investigate how to efficiently combine appearance-based methods and personal calibration for video-based gaze estimation. Previous calibration methods have learned an average model for all persons and then adapted it for a specific person. In contrast, we directly learn a model for personalized gaze estimation where the personal variations are modeled as a low-dimensional latent parameter space. During training, the network learns an efficient way to leverage these parameters for estimating gaze. After training, little person-specific data is required to optimize these (few) parameters. In fact, by calibrating only six parameters per person, the accuracy can be improved by a factor of up to 2.5, and reaches the same level as person-specific models. 
 We assess the performance of our method on a large dataset, consisting of high resolution images taken from near-infrared cameras with active illumination. As it turns out, our method is the first appearance-based approach to gaze estimation to reach the same level of accuracy as involved model-based methods. We further demonstrate that it outperforms existing approaches on two datasets with relatively low-resolution images, MPIIGaze and GazeCapture. Finally, we show using a synthetic dataset created using UnityEyes tools, that our method efficiently predicts 3D gaze (origin and direction of gaze) without the need of explicitly 3D-annotated training data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.00664](http://arxiv.org/abs/1807.00664)

##### PDF
[http://arxiv.org/pdf/1807.00664](http://arxiv.org/pdf/1807.00664)

