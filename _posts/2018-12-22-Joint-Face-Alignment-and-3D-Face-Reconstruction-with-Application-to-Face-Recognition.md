---
layout: post
title: "Joint Face Alignment and 3D Face Reconstruction with Application to Face Recognition"
date: 2018-12-22 02:32:28
categories: arXiv_CV
tags: arXiv_CV Face Relation Recognition Face_Recognition
author: Feng Liu, Qijun Zhao, Xiaoming Liu, Dan Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
Face alignment and 3D face reconstruction are traditionally accomplished as separated tasks. By exploring the strong correlation between 2D landmarks and 3D shapes, in contrast, we propose a joint face alignment and 3D face reconstruction method to simultaneously solve these two problems for 2D face images of arbitrary poses and expressions. This method, based on a summation model of 3D faces and cascaded regression in 2D and 3D shape spaces, iteratively and alternately applies two cascaded regressors, one for updating 2D landmarks and the other for 3D shape. The 3D shape and the landmarks are correlated via a 3D-to-2D mapping matrix, which is updated in each iteration to refine the location and visibility of 2D landmarks. Unlike existing methods, the proposed method can fully automatically generate both pose-and-expression-normalized (PEN) and expressive 3D faces and localize both visible and invisible 2D landmarks. Based on the PEN 3D faces, we devise a method to enhance face recognition accuracy across poses and expressions. Both linear and nonlinear implementations of the proposed method are presented and evaluated in this paper. Extensive experiments show that the proposed method can achieve the state-of-the-art accuracy in both face alignment and 3D face reconstruction, and benefit face recognition owing to its reconstructed PEN 3D face.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1708.02734](http://arxiv.org/abs/1708.02734)

##### PDF
[http://arxiv.org/pdf/1708.02734](http://arxiv.org/pdf/1708.02734)

