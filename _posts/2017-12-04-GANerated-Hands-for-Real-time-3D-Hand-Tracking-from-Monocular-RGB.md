---
layout: post
title: "GANerated Hands for Real-time 3D Hand Tracking from Monocular RGB"
date: 2017-12-04 13:20:25
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN
author: Franziska Mueller, Florian Bernard, Oleksandr Sotnychenko, Dushyant Mehta, Srinath Sridhar, Dan Casas, Christian Theobalt
---

* content
{:toc}

##### Abstract
We address the highly challenging problem of real-time 3D hand tracking based on a monocular RGB-only sequence. Our tracking method combines a convolutional neural network with a kinematic 3D hand model, such that it generalizes well to unseen data, is robust to occlusions and varying camera viewpoints, and leads to anatomically plausible as well as temporally smooth hand motions. For training our CNN we propose a novel approach for the synthetic generation of training data that is based on a geometrically consistent image-to-image translation network. To be more specific, we use a neural network that translates synthetic images to "real" images, such that the so-generated images follow the same statistical distribution as real-world hand images. For training this translation network we combine an adversarial loss and a cycle-consistency loss with a geometric consistency loss in order to preserve geometric properties (such as hand pose) during translation. We demonstrate that our hand tracking system outperforms the current state-of-the-art on challenging RGB-only footage.

##### Abstract (translated by Google)
我们解决了基于单目RGB-only序列的实时3D手部跟踪这一极具挑战性的问题。我们的跟踪方法将卷积神经网络与运动学3D手模型相结合，使其能够很好地推广到不可见的数据，对于遮挡和不同的相机视点具有鲁棒性，并且导致解剖学上合理的以及时间上平滑的手部运动。为了训练我们的CNN，我们提出了一种基于几何一致的图像到图像翻译网络的合成生成训练数据的新方法。更具体地说，我们使用将合成图像翻译成“真实”图像的神经网络，使得如此生成的图像遵循与真实世界手图像相同的统计分布。为了训练这个翻译网络，我们将对抗性损失和循环一致性损失与几何一致性损失相结合，以便在翻译期间保持几何特性（例如手姿势）。我们证明，我们的手部追踪系统胜过目前最具挑战性的仅限于RGB的镜头。

##### URL
[http://arxiv.org/abs/1712.01057](http://arxiv.org/abs/1712.01057)

