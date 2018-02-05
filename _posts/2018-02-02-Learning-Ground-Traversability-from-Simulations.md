---
layout: post
title: "Learning Ground Traversability from Simulations"
date: 2018-02-02 14:50:22
categories: arXiv_RO
tags: arXiv_RO CNN Classification
author: R. Omar Chavez-Garcia, Jerome Guzzi, Luca M. Gambardella, Alessandro Giusti
mathjax: true
---

* content
{:toc}

##### Abstract
Mobile ground robots operating on unstructured terrain must predict which areas of the environment they are able to pass in order to plan feasible paths. We address traversability estimation as a heightmap classification problem: we build a convolutional neural network that, given an image representing the heightmap of a terrain patch, predicts whether the robot will be able to traverse such patch from left to right. The classifier is trained for a specific robot model (wheeled, tracked, legged, snake-like) using simulation data on procedurally generated training terrains; the trained classifier can be applied to unseen large heightmaps to yield oriented traversability maps, and then plan traversable paths. We extensively evaluate the approach in simulation on six real-world elevation datasets, and run a real-robot validation in one indoor and one outdoor environment.

##### Abstract (translated by Google)
在非结构化地形上运行的移动地面机器人必须预测他们能够通过哪些环境区域，以便规划可行的路径。我们将可遍历性估计作为一个高度图分类问题来解决：我们建立一个卷积神经网络，给定表示地形贴片高度图的图像，预测机器人是否能够从左到右遍历这个补丁。使用关于程序生成的训练场地的模拟数据对分类器进行训练以用于特定的机器人模型（轮式，履带式，腿式，蛇形）训练好的分类器可以应用于看不见的大高度图以产生定向的可穿越性地图，然后规划可穿越的路径。我们广泛评估了六个真实世界高程数据集的仿真方法，并在一个室内和一个室外环境中运行实际的机器人验证。

##### URL
[http://arxiv.org/abs/1709.05368](http://arxiv.org/abs/1709.05368)

##### PDF
[http://arxiv.org/pdf/1709.05368](http://arxiv.org/pdf/1709.05368)

