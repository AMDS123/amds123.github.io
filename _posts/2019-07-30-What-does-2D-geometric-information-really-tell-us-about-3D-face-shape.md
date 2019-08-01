---
layout: post
title: "What does 2D geometric information really tell us about 3D face shape?"
date: 2019-07-30 19:08:29
categories: arXiv_CV
tags: arXiv_CV Face Quantitative
author: Anil Bas, William A. P. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
A face image contains geometric cues in the form of configurational information and contours that can be used to estimate 3D face shape. While it is clear that 3D reconstruction from 2D points is highly ambiguous if no further constraints are enforced, one might expect that the face-space constraint solves this problem. We show that this is not the case and that geometric information is an ambiguous cue. There are two sources for this ambiguity. The first is that, within the space of 3D face shapes, there are flexibility modes that remain when some parts of the face are fixed. The second occurs only under perspective projection and is a result of perspective transformation as camera distance varies. Two different faces, when viewed at different distances, can give rise to the same 2D geometry. To demonstrate these ambiguities, we develop new algorithms for fitting a 3D morphable model to 2D landmarks or contours under either orthographic or perspective projection and show how to compute flexibility modes for both cases. We show that both fitting problems can be posed as a separable nonlinear least squares problem and solved efficiently. We demonstrate both quantitatively and qualitatively that the ambiguity is present in reconstructions from geometric information alone but also in reconstructions from a state-of-the-art CNN-based method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1708.06703](http://arxiv.org/abs/1708.06703)

##### PDF
[http://arxiv.org/pdf/1708.06703](http://arxiv.org/pdf/1708.06703)

