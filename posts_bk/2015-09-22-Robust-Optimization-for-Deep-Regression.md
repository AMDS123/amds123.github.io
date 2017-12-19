---
layout: post
title: "Robust Optimization for Deep Regression"
date: 2015-09-22 15:24:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Pose_Estimation CNN Optimization Detection
author: Vasileios Belagiannis, Christian Rupprecht, Gustavo Carneiro, Nassir Navab
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (ConvNets) have successfully contributed to improve the accuracy of regression-based methods for computer vision tasks such as human pose estimation, landmark localization, and object detection. The network optimization has been usually performed with L2 loss and without considering the impact of outliers on the training process, where an outlier in this context is defined by a sample estimation that lies at an abnormal distance from the other training sample estimations in the objective space. In this work, we propose a regression model with ConvNets that achieves robustness to such outliers by minimizing Tukey's biweight function, an M-estimator robust to outliers, as the loss function for the ConvNet. In addition to the robust loss, we introduce a coarse-to-fine model, which processes input images of progressively higher resolutions for improving the accuracy of the regressed values. In our experiments, we demonstrate faster convergence and better generalization of our robust loss function for the tasks of human pose estimation and age estimation from face images. We also show that the combination of the robust loss function with the coarse-to-fine model produces comparable or better results than current state-of-the-art approaches in four publicly available human pose estimation datasets.

##### Abstract (translated by Google)
卷积神经网络（ConvNets）已成功地提高了计算机视觉任务（如人体姿态估计，地标定位和物体检测）的基于回归的方法的准确性。网络优化通常是在L2损失的情况下进行的，而不考虑异常值对训练过程的影响，在这种情况下，异常点是由样本估计定义的，该样本估计位于与目标空间中的其他训练样本估计的距离不正确。在这项工作中，我们提出了一个ConvNet的回归模型，通过将Tukey的权重函数（一个对异常值有效的M估计器）最小化为ConvNet的损失函数来实现对这些异常值的鲁棒性。除了鲁棒性的损失之外，我们引入了粗到精的模型，它处理逐渐提高的分辨率的输入图像，以提高回归值的准确性。在我们的实验中，我们证明了人脸姿态估计和人脸年龄估计任务的快速收敛性和鲁棒损失函数的更一般化。我们还表明，在四个公开可用的人体姿态估计数据集中，鲁棒损失函数与粗到精模型的组合产生与当前最先进的方法相当或更好的结果。

##### URL
[https://arxiv.org/abs/1505.06606](https://arxiv.org/abs/1505.06606)

##### PDF
[https://arxiv.org/pdf/1505.06606](https://arxiv.org/pdf/1505.06606)

