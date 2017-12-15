---
layout: post
title: "'What happens if...' Learning to Predict the Effect of Forces in Images"
date: 2016-03-17 18:12:33
categories: arXiv_CV
tags: arXiv_CV CNN RNN
author: Roozbeh Mottaghi, Mohammad Rastegari, Abhinav Gupta, Ali Farhadi
mathjax: true
---

* content
{:toc}

##### Abstract
What happens if one pushes a cup sitting on a table toward the edge of the table? How about pushing a desk against a wall? In this paper, we study the problem of understanding the movements of objects as a result of applying external forces to them. For a given force vector applied to a specific location in an image, our goal is to predict long-term sequential movements caused by that force. Doing so entails reasoning about scene geometry, objects, their attributes, and the physical rules that govern the movements of objects. We design a deep neural network model that learns long-term sequential dependencies of object movements while taking into account the geometry and appearance of the scene by combining Convolutional and Recurrent Neural Networks. Training our model requires a large-scale dataset of object movements caused by external forces. To build a dataset of forces in scenes, we reconstructed all images in SUN RGB-D dataset in a physics simulator to estimate the physical movements of objects caused by external forces applied to them. Our Forces in Scenes (ForScene) dataset contains 10,335 images in which a variety of external forces are applied to different types of objects resulting in more than 65,000 object movements represented in 3D. Our experimental evaluations show that the challenging task of predicting long-term movements of objects as their reaction to external forces is possible from a single image.

##### Abstract (translated by Google)
如果把桌子上的杯子推向桌子边缘，会发生什么？把桌子推到墙上怎么样？在这篇文章中，我们研究了理解物体运动的问题，因为运用了外力。对于应用于图像中特定位置的给定力矢量，我们的目标是预测由该力引起的长时间连续运动。这样做需要推理场景的几何形状，物体，属性以及管理物体运动的物理规则。我们设计了一个深度神经网络模型，通过结合卷积和递归神经网络来考虑物体的几何和外观，从而学习物体运动的长期顺序依赖性。训练我们的模型需要一个由外力引起的物体运动的大规模数据集。为了在场景中建立力的数据集，我们在物理模拟器中重建了SUN RGB-D数据集中的所有图像，以估计由施加到其上的外力引起的物体的物理运动。我们在场景中的力量（ForScene）数据集包含10,335个图像，其中各种外力施加到不同类型的对象上，导致以3D表示的超过65,000个对象移动。我们的实验评估表明，预测物体长期运动作为其对外力的反应的具有挑战性的任务是可能的，从一个单一的形象。

##### URL
[https://arxiv.org/abs/1603.05600](https://arxiv.org/abs/1603.05600)

##### PDF
[https://arxiv.org/pdf/1603.05600](https://arxiv.org/pdf/1603.05600)

