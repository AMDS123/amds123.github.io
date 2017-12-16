---
layout: post
title: "Learning Less is More - 6D Camera Localization via 3D Surface Regression"
date: 2017-11-28 11:11:03
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Eric Brachmann, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
Popular research areas like autonomous driving and augmented reality have renewed the interest in image-based camera localization. In this work, we address the task of predicting the 6D camera pose from a single RGB image in a given 3D environment. With the advent of neural networks, previous works have either learned the entire camera localization process, or multiple components of a camera localization pipeline. Our key contribution is to demonstrate and explain that learning a single component of this pipeline is sufficient. This component is a fully convolutional neural network for densely regressing so-called scene coordinates, defining the correspondence between the input image and the 3D scene space. The neural network is prepended to a new end-to-end trainable pipeline. Our system is efficient, highly accurate, robust in training, and exhibits outstanding generalization capabilities. It exceeds state-of-the-art consistently on indoor and outdoor datasets. Interestingly, our approach surpasses existing techniques even without utilizing a 3D model of the scene during training, since the network is able to discover 3D scene geometry automatically, solely from single-view constraints.

##### Abstract (translated by Google)
像自主驾驶和增强现实这样的热门研究领域已经重新引起了基于图像的相机定位的兴趣。在这项工作中，我们解决了在给定的3D环境中从单个RGB图像预测6D相机姿态的任务。随着神经网络的出现，以前的作品已经学习了整个相机定位过程，或者是相机定位流水线的多个组成部分。我们的主要贡献是演示和解释，学习这个管道的单一组件是足够的。该分量是一个完全卷积神经网络，用于密集回归所谓的场景坐标，定义输入图像与3D场景空间之间的对应关系。神经网络是一个新的端到端可训练管道。我们的系统是高效，高度准确，强大的培训，并展现出杰出的泛化能力。它在室内和室外数据集上始终超越最先进的技术。有趣的是，我们的方法甚至超越了现有技术，即使在训练期间不利用场景的3D模型，因为网络能够自动地发现3D场景几何，仅从单视图约束。

##### URL
[https://arxiv.org/abs/1711.10228](https://arxiv.org/abs/1711.10228)

##### PDF
[https://arxiv.org/pdf/1711.10228](https://arxiv.org/pdf/1711.10228)

