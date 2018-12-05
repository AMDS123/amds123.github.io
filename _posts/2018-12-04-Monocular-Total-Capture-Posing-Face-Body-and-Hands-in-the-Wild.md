---
layout: post
title: "Monocular Total Capture: Posing Face, Body, and Hands in the Wild"
date: 2018-12-04 18:55:33
categories: arXiv_CV
tags: arXiv_CV Face Tracking CNN Quantitative
author: Donglai Xiang, Hanbyul Joo, Yaser Sheikh
mathjax: true
---

* content
{:toc}

##### Abstract
We present the first method to capture the 3D total motion of a target person from a monocular view input. Given an image or a monocular video, our method reconstructs the motion from body, face, and fingers represented by a 3D deformable mesh model. We use an efficient representation called 3D Part Orientation Fields (POFs), to encode the 3D orientations of all body parts in the common 2D image space. POFs are predicted by a Fully Convolutional Network (FCN), along with the joint confidence maps. To train our network, we collect a new 3D human motion dataset capturing diverse total body motion of 40 subjects in a multiview system. We leverage a 3D deformable human model to reconstruct total body pose from the CNN outputs by exploiting the pose and shape prior in the model. We also present a texture-based tracking method to obtain temporally coherent motion capture output. We perform thorough quantitative evaluations including comparison with the existing body-specific and hand-specific methods, and performance analysis on camera viewpoint and human pose changes. Finally, we demonstrate the results of our total body motion capture on various challenging in-the-wild videos. Our code and newly collected human motion dataset will be publicly shared.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01598](http://arxiv.org/abs/1812.01598)

##### PDF
[http://arxiv.org/pdf/1812.01598](http://arxiv.org/pdf/1812.01598)

