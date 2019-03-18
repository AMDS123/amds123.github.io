---
layout: post
title: "Adversarial Joint Image and Pose Distribution Learning for Camera Pose Regression and Refinement"
date: 2019-03-15 16:32:51
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Pose_Estimation CNN Relation
author: Mai Bui, Christoph Baur, Nassir Navab, Slobodan Ilic, Shadi Albarqouni
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a deep-learning based framework for direct camera pose regression and refinement using RGB information only. For this aim we introduce a novel framework for camera pose estimation, that regresses the camera pose as well as offers a solely RGB-based solution for camera pose refinement. Utilizing research results of recent camera pose regression methods, we investigate the effect of adversarial networks on convolutional neural networks (CNNs) trained for camera re-localization applications, with the goal to better learn the geometric connection between camera pose and corresponding RGB image. Similar to Generative Adversarial Networks (GANs), in addition to a camera pose regressor, mapping images to poses, we propose to train a discriminator that effectively distinguishes between regressed and ground truth poses. This pose discriminator is conditioned on features extracted from the respective input image to implicitly model the relationship between ground truth or regressed poses, and once learned can be used to update the predicted camera poses and improve the localization accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06646](http://arxiv.org/abs/1903.06646)

##### PDF
[http://arxiv.org/pdf/1903.06646](http://arxiv.org/pdf/1903.06646)

