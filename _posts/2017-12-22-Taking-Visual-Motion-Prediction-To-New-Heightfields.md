---
layout: post
title: "Taking Visual Motion Prediction To New Heightfields"
date: 2017-12-22 13:22:14
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Sebastien Ehrhardt, Aron Monszpart, Niloy Mitra, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
While the basic laws of Newtonian mechanics are well understood, explaining a physical scenario still requires manually modeling the problem with suitable equations and estimating the associated parameters. In order to be able to leverage the approximation capabilities of artificial intelligence techniques in such physics related contexts, researchers have handcrafted the relevant states, and then used neural networks to learn the state transitions using simulation runs as training data. Unfortunately, such approaches are unsuited for modeling complex real-world scenarios, where manually authoring relevant state spaces tend to be tedious and challenging. In this work, we investigate if neural networks can implicitly learn physical states of real-world mechanical processes only based on visual data while internally modeling non-homogeneous environment and in the process enable long-term physical extrapolation. We develop a recurrent neural network architecture for this task and also characterize resultant uncertainties in the form of evolving variance estimates. We evaluate our setup to extrapolate motion of rolling ball(s) on bowls of varying shape and orientation, and on arbitrary heightfields using only images as input. We report significant improvements over existing image-based methods both in terms of accuracy of predictions and complexity of scenarios; and report competitive performance with approaches that, unlike us, assume access to internal physical states.

##### Abstract (translated by Google)
虽然牛顿力学的基本定律是很好理解的，但解释物理场景仍然需要用合适的方程手动建模问题并估计相关的参数。为了能够利用人工智能技术在这种物理相关背景下的逼近能力，研究人员已经手工制作了相关的状态，然后使用神经网络来学习状态转换，使用模拟运行作为训练数据。不幸的是，这样的方法不适合建模复杂的现实世界场景，手动编写相关的状态空间往往是单调乏味和具有挑战性的。在这项工作中，我们调查神经网络是否可以隐式地学习真实世界的机械过程的物理状态，仅仅基于视觉数据，而在内部建模非均匀环境，并且在这个过程中能够进行长期的物理外推。我们针对这一任务开发了一个递归的神经网络架构，并以变化的方差估计的形式表征了由此产生的不确定性。我们评估我们的设置，以推断不同形状和方向的碗上滚球的运动，以及仅使用图像作为输入的任意高度场上的运动。我们报告在现有的基于图像的方法方面的重大改进，无论是在预测的准确性和场景的复杂性方面，并用不同于我们的方法来报告具有竞争力的表现。

##### URL
[http://arxiv.org/abs/1712.09448](http://arxiv.org/abs/1712.09448)

##### PDF
[http://arxiv.org/pdf/1712.09448](http://arxiv.org/pdf/1712.09448)

