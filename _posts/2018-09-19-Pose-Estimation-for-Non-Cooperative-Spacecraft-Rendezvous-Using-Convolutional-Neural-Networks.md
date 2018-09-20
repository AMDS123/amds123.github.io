---
layout: post
title: "Pose Estimation for Non-Cooperative Spacecraft Rendezvous Using Convolutional Neural Networks"
date: 2018-09-19 15:19:45
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Classification
author: Sumant Sharma, Connor Beierle, Simone D&#x27;Amico
mathjax: true
---

* content
{:toc}

##### Abstract
On-board estimation of the pose of an uncooperative target spacecraft is an essential task for future on-orbit servicing and close-proximity formation flying missions. However, two issues hinder reliable on-board monocular vision based pose estimation: robustness to illumination conditions due to a lack of reliable visual features and scarcity of image datasets required for training and benchmarking. To address these two issues, this work details the design and validation of a monocular vision based pose determination architecture for spaceborne applications. The primary contribution to the state-of-the-art of this work is the introduction of a novel pose determination method based on Convolutional Neural Networks (CNN) to provide an initial guess of the pose in real-time on-board. The method involves discretizing the pose space and training the CNN with images corresponding to the resulting pose labels. Since reliable training of the CNN requires massive image datasets and computational resources, the parameters of the CNN must be determined prior to the mission with synthetic imagery. Moreover, reliable training of the CNN requires datasets that appropriately account for noise, color, and illumination characteristics expected in orbit. Therefore, the secondary contribution of this work is the introduction of an image synthesis pipeline, which is tailored to generate high fidelity images of any spacecraft 3D model. The proposed technique is scalable to spacecraft of different structural and physical properties as well as robust to the dynamic illumination conditions of space. Through metrics measuring classification and pose accuracy, it is shown that the presented architecture has desirable robustness and scalable properties.

##### Abstract (translated by Google)
机上估计不合作目标航天器的姿态是未来在轨服务和近距离编队飞行任务的重要任务。然而，两个问题阻碍了基于单眼视觉的可靠姿势估计的可靠性：由于缺乏可靠的视觉特征而导致的光照条件的稳健性以及训练和基准测试所需的图像数据集的稀缺性。为解决这两个问题，本工作详细介绍了基于单眼视觉的星载应用姿态确定架构的设计和验证。对这项工作的最新技术的主要贡献是引入基于卷积神经网络（CNN）的新颖姿势确定方法，以在船上实时提供姿势的初始猜测。该方法涉及使姿势空间离散化并且使CNN训练与对应于所得姿势标签的图像。由于CNN的可靠训练需要大量的图像数据集和计算资源，因此必须在使用合成图像执行任务之前确定CNN的参数。此外，CNN的可靠训练需要适当考虑轨道中预期的噪声，颜色和照明特性的数据集。因此，这项工作的次要贡献是引入了图像合成管道，该管道被定制为生成任何航天器3D模型的高保真图像。所提出的技术可扩展到具有不同结构和物理特性的航天器，并且对空间的动态照明条件具有鲁棒性。通过度量测量分类和姿势准确性，显示所呈现的体系结构具有期望的鲁棒性和可伸缩性质。

##### URL
[http://arxiv.org/abs/1809.07238](http://arxiv.org/abs/1809.07238)

##### PDF
[http://arxiv.org/pdf/1809.07238](http://arxiv.org/pdf/1809.07238)

