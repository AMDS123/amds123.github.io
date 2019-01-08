---
layout: post
title: "NVS Machines: Learning Novel View Synthesis with Fine-grained View Control"
date: 2019-01-07 15:24:25
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Xu Chen, Jie Song, Otmar Hilliges
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach that learns to synthesize high-quality, novel views of 3D objects or scenes, while providing fine-grained and precise control over the 6-DOF viewpoint. The approach is self-supervised and only requires 2D images and associated view transforms for training. Our main contribution is a network architecture that leverages a transforming auto-encoder in combination with a depth-guided warping procedure to predict geometrically accurate unseen views. Leveraging geometric constraints renders direct supervision via depth or flow maps unnecessary. If large parts of the object are occluded in the source view, a purely learning based prior is used to predict the values for dis-occluded pixels. Our network furthermore predicts a per-pixel mask, used to fuse depth-guided and pixel-based predictions. The resulting images reflect the desired 6-DOF transformation and details are preserved. We thoroughly evaluate our architecture on synthetic and real scenes and under fine-grained and fixed-view settings. Finally, we demonstrate that the approach generalizes to entirely unseen images such as product images downloaded from the internet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01880](http://arxiv.org/abs/1901.01880)

##### PDF
[http://arxiv.org/pdf/1901.01880](http://arxiv.org/pdf/1901.01880)

