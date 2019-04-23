---
layout: post
title: "Consistent Generative Query Networks"
date: 2019-04-22 00:51:13
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Ananya Kumar, S. M. Ali Eslami, Danilo J. Rezende, Marta Garnelo, Fabio Viola, Edward Lockhart, Murray Shanahan
mathjax: true
---

* content
{:toc}

##### Abstract
Stochastic video prediction models take in a sequence of image frames, and generate a sequence of consecutive future image frames. These models typically generate future frames in an autoregressive fashion, which is slow and requires the input and output frames to be consecutive. We introduce a model that overcomes these drawbacks by generating a latent representation from an arbitrary set of frames that can then be used to simultaneously and efficiently sample temporally consistent frames at arbitrary time-points. For example, our model can "jump" and directly sample frames at the end of the video, without sampling intermediate frames. Synthetic video evaluations confirm substantial gains in speed and functionality without loss in fidelity. We also apply our framework to a 3D scene reconstruction dataset. Here, our model is conditioned on camera location and can sample consistent sets of images for what an occluded region of a 3D scene might look like, even if there are multiple possibilities for what that region might contain. Reconstructions and videos are available at https://bit.ly/2O4Pc4R.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.02033](http://arxiv.org/abs/1807.02033)

##### PDF
[http://arxiv.org/pdf/1807.02033](http://arxiv.org/pdf/1807.02033)

