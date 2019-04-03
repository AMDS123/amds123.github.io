---
layout: post
title: "DeepLight: Learning Illumination for Unconstrained Mobile Mixed Reality"
date: 2019-04-02 02:15:09
categories: arXiv_CV
tags: arXiv_CV Inference
author: Chloe LeGendre, Wan-Chun Ma, Graham Fyffe, John Flynn, Laurent Charbonnel, Jay Busch, Paul Debevec
mathjax: true
---

* content
{:toc}

##### Abstract
We present a learning-based method to infer plausible high dynamic range (HDR), omnidirectional illumination given an unconstrained, low dynamic range (LDR) image from a mobile phone camera with a limited field of view (FOV). For training data, we collect videos of various reflective spheres placed within the camera's FOV, leaving most of the background unoccluded, leveraging that materials with diverse reflectance functions reveal different lighting cues in a single exposure. We train a deep neural network to regress from the LDR background image to HDR lighting by matching the LDR ground truth sphere images to those rendered with the predicted illumination using image-based relighting, which is differentiable. Our inference runs at interactive frame rates on a mobile device, enabling realistic rendering of virtual objects into real scenes for mobile mixed reality. Training on automatically exposed and white-balanced videos, we improve the realism of rendered objects compared to the state-of-the art methods for both indoor and outdoor scenes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01175](http://arxiv.org/abs/1904.01175)

##### PDF
[http://arxiv.org/pdf/1904.01175](http://arxiv.org/pdf/1904.01175)

