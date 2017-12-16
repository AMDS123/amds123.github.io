---
layout: post
title: "Towards Visual Ego-motion Learning in Robots"
date: 2017-05-29 16:25:50
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Sudeep Pillai, John J. Leonard
mathjax: true
---

* content
{:toc}

##### Abstract
Many model-based Visual Odometry (VO) algorithms have been proposed in the past decade, often restricted to the type of camera optics, or the underlying motion manifold observed. We envision robots to be able to learn and perform these tasks, in a minimally supervised setting, as they gain more experience. To this end, we propose a fully trainable solution to visual ego-motion estimation for varied camera optics. We propose a visual ego-motion learning architecture that maps observed optical flow vectors to an ego-motion density estimate via a Mixture Density Network (MDN). By modeling the architecture as a Conditional Variational Autoencoder (C-VAE), our model is able to provide introspective reasoning and prediction for ego-motion induced scene-flow. Additionally, our proposed model is especially amenable to bootstrapped ego-motion learning in robots where the supervision in ego-motion estimation for a particular camera sensor can be obtained from standard navigation-based sensor fusion strategies (GPS/INS and wheel-odometry fusion). Through experiments, we show the utility of our proposed approach in enabling the concept of self-supervised learning for visual ego-motion estimation in autonomous robots.

##### Abstract (translated by Google)
在过去的十年中，已经提出了许多基于模型的视觉内测（VO）算法，其经常局限于相机光学器件的类型，或者观察到的底层运动流形。我们设想机器人能够在最低限度的监督环境中学习和执行这些任务，因为他们获得了更多的经验。为此，我们提出了一个完全可训练的解决方案，用于各种相机光学系统的视觉自我运动估计。我们提出了一个视觉的自我运动学习架构，通过混合密度网络（MDN）将观察到的光流向量映射到自我运动密度估计。通过将体系结构建模为条件变分自动编码器（C-VAE），我们的模型能够为自我运动引起的场景流提供内省的推理和预测。另外，我们提出的模型特别适合于在机器人中引导自我运动学习，其中可以从标准的基于导航的传感器融合策略（GPS / INS和车轮 - 测距融合）获得针对特定相机传感器的自我运动估计的监督， 。通过实验，我们展示了我们提出的方法的实用性，使自主机器人中的视觉自我运动估计的自监督学习的概念成为可能。

##### URL
[https://arxiv.org/abs/1705.10279](https://arxiv.org/abs/1705.10279)

##### PDF
[https://arxiv.org/pdf/1705.10279](https://arxiv.org/pdf/1705.10279)

