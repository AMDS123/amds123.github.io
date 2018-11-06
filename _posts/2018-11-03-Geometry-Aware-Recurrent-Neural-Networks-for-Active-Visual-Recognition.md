---
layout: post
title: "Geometry-Aware Recurrent Neural Networks for Active Visual Recognition"
date: 2018-11-03 22:24:00
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation RNN Detection Recognition
author: Ricson Cheng, Ziyan Wang, Katerina Fragkiadaki
mathjax: true
---

* content
{:toc}

##### Abstract
We present recurrent geometry-aware neural networks that integrate visual information across multiple views of a scene into 3D latent feature tensors, while maintaining an one-to-one mapping between 3D physical locations in the world scene and latent feature locations. Object detection, object segmentation, and 3D reconstruction is then carried out directly using the constructed 3D feature memory, as opposed to any of the input 2D images. The proposed models are equipped with differentiable egomotion-aware feature warping and (learned) depth-aware unprojection operations to achieve geometrically consistent mapping between the features in the input frame and the constructed latent model of the scene. We empirically show the proposed model generalizes much better than geometryunaware LSTM/GRU networks, especially under the presence of multiple objects and cross-object occlusions. Combined with active view selection policies, our model learns to select informative viewpoints to integrate information from by "undoing" cross-object occlusions, seamlessly combining geometry with learning from experience.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01292](http://arxiv.org/abs/1811.01292)

##### PDF
[http://arxiv.org/pdf/1811.01292](http://arxiv.org/pdf/1811.01292)

