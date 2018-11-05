---
layout: post
title: "Adversarial Learning of Structure-Aware Fully Convolutional Networks for Landmark Localization"
date: 2018-11-02 06:14:42
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Pose_Estimation CNN Prediction
author: Yu Chen, Chunhua Shen, Hao Chen, Xiu-Shen Wei, Lingqiao Liu, Jian Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Landmark/pose estimation in single monocular images have received much effort in computer vision due to its important applications. It remains a challenging task when input images severe occlusions caused by, e.g., adverse camera views. Under such circumstances, biologically implausible pose predictions may be produced. In contrast, human vision is able to predict poses by exploiting geometric constraints of landmark point inter-connectivity. To address the problem, by incorporating priors about the structure of pose components, we propose a novel structure-aware fully convolutional network to implicitly take such priors into account during training of the deep network. Explicit learning of such constraints is typically challenging. Instead, inspired by how human identifies implausible poses, we design discriminators to distinguish the real poses from the fake ones (such as biologically implausible ones). If the pose generator G generates results that the discriminator fails to distinguish from real ones, the network successfully learns the priors. Training of the network follows the strategy of conditional Generative Adversarial Networks (GANs). The effectiveness of the proposed network is evaluated on three pose-related tasks: 2D single human pose estimation, 2D facial landmark estimation and 3D single human pose estimation. The proposed approach significantly outperforms the state-of-the-art methods and almost always generates plausible pose predictions, demonstrating the usefulness of implicit learning of structures using GANs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1711.00253](http://arxiv.org/abs/1711.00253)

##### PDF
[http://arxiv.org/pdf/1711.00253](http://arxiv.org/pdf/1711.00253)

