---
layout: post
title: "Iris Presentation Attack Detection Based on Photometric Stereo Features"
date: 2018-11-18 01:21:22
categories: arXiv_CV
tags: arXiv_CV Face Classification Detection
author: Adam Czajka, Zhaoyuan Fang, Kevin W. Bowyer
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new iris presentation attack detection method using three-dimensional features of an observed iris region estimated by photometric stereo. Our implementation uses a pair of iris images acquired by a common commercial iris sensor (LG 4000). No hardware modifications of any kind are required. Our approach should be applicable to any iris sensor that can illuminate the eye from two different directions. Each iris image in the pair is captured under near-infrared illumination at a different angle relative to the eye. Photometric stereo is used to estimate surface normal vectors in the non-occluded portions of the iris region. The variability of the normal vectors is used as the presentation attack detection score. This score is larger for a texture that is irregularly opaque and printed on a convex contact lens, and is smaller for an authentic iris texture. Thus the problem is formulated as binary classification into (a) an eye wearing textured contact lens and (b) the texture of an actual iris surface (possibly seen through a clear contact lens). Experiments were carried out on a database of approx. 2,900 iris image pairs acquired from approx. 100 subjects. Our method was able to correctly classify over 95% of samples when tested on contact lens brands unseen in training, and over 98% of samples when the contact lens brand was seen during training. The source codes of the method are made available to other researchers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07252](http://arxiv.org/abs/1811.07252)

##### PDF
[http://arxiv.org/pdf/1811.07252](http://arxiv.org/pdf/1811.07252)

