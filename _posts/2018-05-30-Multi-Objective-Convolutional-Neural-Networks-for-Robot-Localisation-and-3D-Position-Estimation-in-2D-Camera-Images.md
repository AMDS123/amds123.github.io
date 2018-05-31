---
layout: post
title: "Multi-Objective Convolutional Neural Networks for Robot Localisation and 3D Position Estimation in 2D Camera Images"
date: 2018-05-30 07:51:37
categories: arXiv_RO
tags: arXiv_RO CNN Deep_Learning Prediction Relation
author: Justinas Miseikis, Inka Brijacak, Saeed Yahyanejad, Kyrre Glette, Ole Jakob Elle, Jim Torresen
mathjax: true
---

* content
{:toc}

##### Abstract
The field of collaborative robotics and human-robot interaction often focuses on the prediction of human behaviour, while assuming the information about the robot setup and configuration being known. This is often the case with fixed setups, which have all the sensors fixed and calibrated in relation to the rest of the system. However, it becomes a limiting factor when the system needs to be reconfigured or moved. We present a deep learning approach, which aims to solve this issue. Our method learns to identify and precisely localise the robot in 2D camera images, so having a fixed setup is no longer a requirement and a camera can be moved. In addition, our approach identifies the robot type and estimates the 3D position of the robot base in the camera image as well as 3D positions of each of the robot joints. Learning is done by using a multi-objective convolutional neural network with four previously mentioned objectives simultaneously using a combined loss function. The multi-objective approach makes the system more flexible and efficient by reusing some of the same features and diversifying for each objective in lower layers. A fully trained system shows promising results in providing an accurate mask of where the robot is located and an estimate of its base and joint positions in 3D. We compare the results to our previous approach of using cascaded convolutional neural networks.

##### Abstract (translated by Google)
协作机器人技术和人机交互领域经常关注人类行为的预测，同时假定机器人设置和配置的信息是已知的。固定设置通常就是这种情况，固定设置的所有传感器都是相对于系统其余部分进行固定和校准的。但是，当系统需要重新配置或移动时，它成为一个限制因素。我们提出了深入的学习方法，旨在解决这个问题。我们的方法学习识别并精确定位2D摄像机图像中的机器人，因此不再需要固定设置，并且可以移动摄像机。另外，我们的方法识别机器人类型并估计机器人基座在相机图像中的3D位置以及每个机器人关节的3D位置。学习是通过使用具有前述四个目标的多目标卷积神经网络使用组合损失函数来完成的。多目标方法通过重复使用某些相同的功能并为较低层中的每个目标多样化，使系统更加灵活和高效。一个训练有素的系统在提供机器人所在位置的准确掩模以及估计其基座和三维关节位置方面显示了很好的结果。我们将结果与我们先前使用级联卷积神经网络的方法进行了比较。

##### URL
[http://arxiv.org/abs/1804.03005](http://arxiv.org/abs/1804.03005)

##### PDF
[http://arxiv.org/pdf/1804.03005](http://arxiv.org/pdf/1804.03005)

