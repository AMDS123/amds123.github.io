---
layout: post
title: "3D-PhysNet: Learning the Intuitive Physics of Non-Rigid Object Deformations"
date: 2018-04-25 15:53:03
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Zhihua Wang, Stefano Rosa, Bo Yang, Sen Wang, Niki Trigoni, Andrew Markham
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to interact and understand the environment is a fundamental prerequisite for a wide range of applications from robotics to augmented reality. In particular, predicting how deformable objects will react to applied forces in real time is a significant challenge. This is further confounded by the fact that shape information about encountered objects in the real world is often impaired by occlusions, noise and missing regions e.g. a robot manipulating an object will only be able to observe a partial view of the entire solid. In this work we present a framework, 3D-PhysNet, which is able to predict how a three-dimensional solid will deform under an applied force using intuitive physics modelling. In particular, we propose a new method to encode the physical properties of the material and the applied force, enabling generalisation over materials. The key is to combine deep variational autoencoders with adversarial training, conditioned on the applied force and the material properties. We further propose a cascaded architecture that takes a single 2.5D depth view of the object and predicts its deformation. Training data is provided by a physics simulator. The network is fast enough to be used in real-time applications from partial views. Experimental results show the viability and the generalisation properties of the proposed architecture.

##### Abstract (translated by Google)
交互和理解环境的能力是从机器人到增强现实的广泛应用的基本先决条件。特别是，预测可变形物体如何实时对施加的力作出反应是一项重大挑战。这进一步受到这样的事实的困扰，即在现实世界中遇到的物体的形状信息经常受到遮挡，噪声和缺失区域的损害，例如，操纵物体的机器人将只能观察整个固体的局部视图。在这项工作中，我们提出了一个框架，3D-PhysNet，它能够预测三维固体如何在使用直观的物理建模的应用力下变形。特别是，我们提出了一种新的方法来编码材料的物理特性和应用力，从而可以推广材料。关键是将深度变分自动编码器与对抗训练结合起来，以施加的力和材料属性为条件。我们进一步提出了一个级联体系结构，该体系结构采用对象的单个2.5D深度视图并预测其变形。训练数据由物理模​​拟器提供。该网络速度足够快，可用于部分视图的实时应用程序。实验结果表明了所提出的体系结构的可行性和泛化性质。

##### URL
[https://arxiv.org/abs/1805.00328](https://arxiv.org/abs/1805.00328)

##### PDF
[https://arxiv.org/pdf/1805.00328](https://arxiv.org/pdf/1805.00328)

