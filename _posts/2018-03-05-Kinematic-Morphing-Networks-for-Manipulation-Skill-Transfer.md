---
layout: post
title: "Kinematic Morphing Networks for Manipulation Skill Transfer"
date: 2018-03-05 17:10:46
categories: arXiv_RO
tags: arXiv_RO Prediction
author: Peter Englert, Marc Toussaint
mathjax: true
---

* content
{:toc}

##### Abstract
The transfer of a robot skill between different geometric environments is non-trivial since a wide variety of environments exists, sensor observations as well as robot motions are high-dimensional, and the environment might only be partially observed. We consider the problem of extracting a low-dimensional description of the manipulated environment in form of a kinematic model. This allows us to transfer a skill by defining a policy on a prototype model and morphing the observed environment to this prototype. A deep neural network is used to map depth image observations of the environment to morphing parameter, which include transformation and configuration parameters of the prototype model. Using the concatenation property of affine transformations and the ability to convert point clouds to depth images allows to apply the network in an iterative manner. The network is trained on data generated in a simulator and on augmented data that is created by using network predictions. The algorithm is evaluated on different tasks, where it is shown that iterative predictions lead to a higher accuracy than one-step predictions.

##### Abstract (translated by Google)
机器人技能在不同几何环境之间的转移并非微不足道，因为存在各种各样的环境，传感器观测以及机器人运动都是高维的，并且环境可能仅被部分观察到。我们考虑以运动学模型的形式提取操作环境的低维描述的问题。这使我们能够通过在原型模型上定义策略并将观察环境变形为原型来转移技能。深度神经网络用于将环境的深度图像观察映射到变形参数，其中包括原型模型的变换和配置参数。使用仿射变换的连接属性和将点云转换为深度图像的能力允许以迭代的方式应用网络。网络训练模拟器中生成的数据和使用网络预测创建的增强数据。该算法在不同的任务上进行评估，其中显示迭代预测导致比一步预测更高的准确性。

##### URL
[http://arxiv.org/abs/1803.01777](http://arxiv.org/abs/1803.01777)

##### PDF
[http://arxiv.org/pdf/1803.01777](http://arxiv.org/pdf/1803.01777)

