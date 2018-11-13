---
layout: post
title: "Deep-learning the Latent Space of Light Transport"
date: 2018-11-12 14:55:58
categories: arXiv_CV
tags: arXiv_CV CNN
author: Pedro Hermosilla, Sebastian Maisch, Tobias Ritschel, Timo Ropinski
mathjax: true
---

* content
{:toc}

##### Abstract
We suggest a method to directly deep-learn light transport, i. e., the mapping from a 3D geometry-illumination-material configuration to a shaded 2D image. While many previous learning methods have employed 2D convolutional neural networks applied to images, we show for the first time that light transport can be learned directly in 3D. The benefit of 3D over 2D is, that the former can also correctly capture illumination effects related to occluded and/or semi-transparent geometry. To learn 3D light transport, we represent the 3D scene as an unstructured 3D point cloud, which is later, during rendering, projected to the 2D output image. Thus, we suggest a two-stage operator comprising of a 3D network that first transforms the point cloud into a latent representation, which is later on projected to the 2D output image using a dedicated 3D-2D network in a second step. We will show that our approach results in improved quality in terms of temporal coherence while retaining most of the computational efficiency of common 2D methods. As a consequence, the proposed two stage-operator serves as a valuable extension to modern deferred shading approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04756](http://arxiv.org/abs/1811.04756)

##### PDF
[http://arxiv.org/pdf/1811.04756](http://arxiv.org/pdf/1811.04756)

