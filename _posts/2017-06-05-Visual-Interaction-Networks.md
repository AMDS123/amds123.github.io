---
layout: post
title: "Visual Interaction Networks"
date: 2017-06-05 17:38:52
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Nicholas Watters, Andrea Tacchetti, Theophane Weber, Razvan Pascanu, Peter Battaglia, Daniel Zoran
mathjax: true
---

* content
{:toc}

##### Abstract
From just a glance, humans can make rich predictions about the future state of a wide range of physical systems. On the other hand, modern approaches from engineering, robotics, and graphics are often restricted to narrow domains and require direct measurements of the underlying states. We introduce the Visual Interaction Network, a general-purpose model for learning the dynamics of a physical system from raw visual observations. Our model consists of a perceptual front-end based on convolutional neural networks and a dynamics predictor based on interaction networks. Through joint training, the perceptual front-end learns to parse a dynamic visual scene into a set of factored latent object representations. The dynamics predictor learns to roll these states forward in time by computing their interactions and dynamics, producing a predicted physical trajectory of arbitrary length. We found that from just six input video frames the Visual Interaction Network can generate accurate future trajectories of hundreds of time steps on a wide range of physical systems. Our model can also be applied to scenes with invisible objects, inferring their future states from their effects on the visible objects, and can implicitly infer the unknown mass of objects. Our results demonstrate that the perceptual module and the object-based dynamics predictor module can induce factored latent representations that support accurate dynamical predictions. This work opens new opportunities for model-based decision-making and planning from raw sensory observations in complex physical environments.

##### Abstract (translated by Google)
从一眼看，人类可以对各种物理系统的未来状态做出丰富的预测。另一方面，工程，机器人和图形等现代方法往往局限于狭义领域，需要直接测量基础状态。我们介绍了视觉交互网络，一个通用的模型，用于从原始的视觉观察中学习物理系统的动力学。我们的模型由基于卷积神经网络的感知前端和基于交互网络的动态预测器组成。通过联合训练，感知前端学习将动态视觉场景解析为一组分解的潜在对象表示。动力学预测器学习通过计算它们的相互作用和动力学来及时推进这些状态，产生任意长度的预测物理轨迹。我们发现，从六个输入视频帧中，视觉交互网络可以在广泛的物理系统上生成数百个时间步长的准确未来轨迹。我们的模型也可以应用于具有不可见物体的场景，根据它们对可见物体的影响来推断它们的未来状态，并且可以隐含地推断未知物体的质量。我们的研究结果表明，感知模块和基于对象的动力学预测模块可以诱导支持精确的动态预测的分解潜在表示。这项工作为在复杂的物理环境中进行原始感官观察开创了基于模型的决策和规划的新机会。

##### URL
[https://arxiv.org/abs/1706.01433](https://arxiv.org/abs/1706.01433)

##### PDF
[https://arxiv.org/pdf/1706.01433](https://arxiv.org/pdf/1706.01433)

