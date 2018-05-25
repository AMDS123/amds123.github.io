---
layout: post
title: "Adversarial Collaboration: Joint Unsupervised Learning of Depth, Camera Motion, Optical Flow and Motion Segmentation"
date: 2018-05-24 17:49:05
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Prediction
author: Anurag Ranjan, Varun Jampani, Kihwan Kim, Deqing Sun, Jonas Wulff, Michael J. Black
mathjax: true
---

* content
{:toc}

##### Abstract
We address the unsupervised learning of several interconnected problems in low-level vision: single view depth prediction, camera motion estimation, optical flow and segmentation of a video into the static scene and moving regions. Our key insight is that these four fundamental vision problems are coupled and, consequently, learning to solve them together simplifies the problem because the solutions can reinforce each other by exploiting known geometric constraints. In order to model geometric constraints, we introduce Adversarial Collaboration, a framework that facilitates competition and collaboration between neural networks. We go beyond previous work by exploiting geometry more explicitly and segmenting the scene into static and moving regions. Adversarial Collaboration works much like expectation-maximization but with neural networks that act as adversaries, competing to explain pixels that correspond to static or moving regions, and as collaborators through a moderator that assigns pixels to be either static or independently moving. Our novel method integrates all these problems in a common framework and simultaneously reasons about the segmentation of the scene into moving objects and the static background, the camera motion, depth of the static scene structure, and the optical flow of moving objects. Our model is trained without any supervision and achieves state of the art results amongst unsupervised methods.

##### Abstract (translated by Google)
我们针对低级视觉中的几个相互关联的问题进行无监督学习：单视点深度预测，相机运动估计，光流以及将视频分割成静态场景和移动区域。我们的关键洞察力是，这四个基本的视觉问题是相互耦合的，因此，一起学习解决它们可以简化问题，因为解决方案可以通过利用已知的几何约束来相互补充。为了对几何约束进行建模，我们引入了敌对协作（Adversarial Collaboration），这是一个促进神经网络之间竞争和协作的框架。我们超越以前的工作，更明确地利用几何图形并将场景分割成静态和移动区域。对抗性协作的作用与期望最大化一样，但具有充当对手的神经网络，竞争解释与静态或移动区域相对应的像素，以及通过主持人分配像素为静态或独立移动的协作者。我们的新方法将所有这些问题都集成在一个共同的框架中，同时还将场景分割为运动物体和静态背景，相机运动，静态场景结构的深度以及运动物体的光流。我们的模型在没有任何监督的情况下接受培训，并在无监督的方法中实现了最先进的结果。

##### URL
[http://arxiv.org/abs/1805.09806](http://arxiv.org/abs/1805.09806)

##### PDF
[http://arxiv.org/pdf/1805.09806](http://arxiv.org/pdf/1805.09806)

