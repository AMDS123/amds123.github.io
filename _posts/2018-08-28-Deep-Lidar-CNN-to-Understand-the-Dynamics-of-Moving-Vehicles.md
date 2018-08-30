---
layout: post
title: "Deep Lidar CNN to Understand the Dynamics of Moving Vehicles"
date: 2018-08-28 20:27:16
categories: arXiv_CV
tags: arXiv_CV Inference Deep_Learning
author: Victor Vaquero, Alberto Sanfeliu, Francesc Moreno-Noguer
mathjax: true
---

* content
{:toc}

##### Abstract
Perception technologies in Autonomous Driving are experiencing their golden age due to the advances in Deep Learning. Yet, most of these systems rely on the semantically rich information of RGB images. Deep Learning solutions applied to the data of other sensors typically mounted on autonomous cars (e.g. lidars or radars) are not explored much. In this paper we propose a novel solution to understand the dynamics of moving vehicles of the scene from only lidar information. The main challenge of this problem stems from the fact that we need to disambiguate the proprio-motion of the 'observer' vehicle from that of the external 'observed' vehicles. For this purpose, we devise a CNN architecture which at testing time is fed with pairs of consecutive lidar scans. However, in order to properly learn the parameters of this network, during training we introduce a series of so-called pretext tasks which also leverage on image data. These tasks include semantic information about vehicleness and a novel lidar-flow feature which combines standard image-based optical flow with lidar scans. We obtain very promising results and show that including distilled image information only during training, allows improving the inference results of the network at test time, even when image data is no longer used.

##### Abstract (translated by Google)
由于深度学习的进步，自主驾驶中的感知技术正在经历其黄金时代。然而，这些系统中的大多数依赖于RGB图像的语义丰富的信息。应用于通常安装在自动驾驶汽车（例如激光雷达或雷达）上的其他传感器的数据的深度学习解决方案没有多少探讨。在本文中，我们提出了一种新颖的解决方案，以便仅从激光雷达信息中了解场景中移动车辆的动态。这个问题的主要挑战源于这样一个事实，即我们需要消除“观察者”车辆与外部“观察”车辆的自行车运动的歧义。为此，我们设计了一种CNN架构，在测试时为其提供成对的连续激光雷达扫描。然而，为了正确地学习该网络的参数，在训练期间我们引入了一系列所谓的前置任务，这些任务也利用了图像数据。这些任务包括有关车辆的语义信息和一种新的激光雷达流动特征，它结合了基于标准图像的光学流与激光雷达扫描。我们获得了非常有希望的结果，并且表明仅在训练期间包括蒸馏图像信息，允许在测试时改善网络的推断结果，即使在不再使用图像数据时也是如此。

##### URL
[http://arxiv.org/abs/1808.09526](http://arxiv.org/abs/1808.09526)

##### PDF
[http://arxiv.org/pdf/1808.09526](http://arxiv.org/pdf/1808.09526)

