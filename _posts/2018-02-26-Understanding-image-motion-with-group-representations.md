---
layout: post
title: "Understanding image motion with group representations"
date: 2018-02-26 17:33:45
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Andrew Jaegle, Stephen Phillips, Daphne Ippolito, Kostas Daniilidis
mathjax: true
---

* content
{:toc}

##### Abstract
Motion is an important signal for agents in dynamic environments, but learning to represent motion from unlabeled video is a difficult and underconstrained problem. We propose a model of motion based on elementary group properties of transformations and use it to train a representation of image motion. While most methods of estimating motion are based on pixel-level constraints, we use these group properties to constrain the abstract representation of motion itself. We demonstrate that a deep neural network trained using this method captures motion in both synthetic 2D sequences and real-world sequences of vehicle motion, without requiring any labels. Networks trained to respect these constraints implicitly identify the image characteristic of motion in different sequence types. In the context of vehicle motion, this method extracts information useful for localization, tracking, and odometry. Our results demonstrate that this representation is useful for learning motion in the general setting where explicit labels are difficult to obtain.

##### Abstract (translated by Google)
运动对于动态环境中的代理来说是一个重要信号，但学习代表未标记视频的运动是一个困难且不受约束的问题。我们基于变换的基本组属性提出了一个运动模型，并用它来训练图像运动的表示。虽然大多数估计运动的方法都是基于像素级约束，但我们使用这些组属性来约束运动本身的抽象表示。我们证明，使用此方法训练的深度神经网络捕获合成2D序列和车辆运动的实际序列中的运动，而不需要任何标签。经过训练以遵守这些约束的网络隐式地识别不同序列类型中的运动的图像特征。在车辆运动的情况下，该方法提取对定位，跟踪和测距有用的信息。我们的结果表明，这种表示对于在显式标签难以获得的一般设置中学习运动是有用的。

##### URL
[http://arxiv.org/abs/1612.00472](http://arxiv.org/abs/1612.00472)

##### PDF
[http://arxiv.org/pdf/1612.00472](http://arxiv.org/pdf/1612.00472)

