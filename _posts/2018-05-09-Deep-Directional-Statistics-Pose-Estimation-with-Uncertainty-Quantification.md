---
layout: post
title: "Deep Directional Statistics: Pose Estimation with Uncertainty Quantification"
date: 2018-05-09 09:22:09
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Inference Deep_Learning Prediction
author: Sergey Prokudin, Peter Gehler, Sebastian Nowozin
mathjax: true
---

* content
{:toc}

##### Abstract
Modern deep learning systems successfully solve many perception tasks such as object pose estimation when the input image is of high quality. However, in challenging imaging conditions such as on low-resolution images or when the image is corrupted by imaging artifacts, current systems degrade considerably in accuracy. While a loss in performance is unavoidable, we would like our models to quantify their uncertainty in order to achieve robustness against images of varying quality. Probabilistic deep learning models combine the expressive power of deep learning with uncertainty quantification. In this paper, we propose a novel probabilistic deep learning model for the task of angular regression. Our model uses von Mises distributions to predict a distribution over object pose angle. Whereas a single von Mises distribution is making strong assumptions about the shape of the distribution, we extend the basic model to predict a mixture of von Mises distributions. We show how to learn a mixture model using a finite and infinite number of mixture components. Our model allows for likelihood-based training and efficient inference at test time. We demonstrate on a number of challenging pose estimation datasets that our model produces calibrated probability predictions and competitive or superior point estimates compared to the current state-of-the-art.

##### Abstract (translated by Google)
当输入图像质量较高时，现代深度学习系统成功地解决了许多感知任务，例如对象姿态估计。但是，在低成像条件下或图像被成像伪像破坏时，目前的系统在精度上会显着降低。虽然性能损失是不可避免的，但我们希望我们的模型能够量化它们的不确定性，以便实现对不同质量图像的鲁棒性。概率深度学习模型将深度学习的表达能力与不确定性量化相结合。在本文中，我们提出了一种新的角度回归任务的概率深度学习模型。我们的模型使用von Mises分布来预测物体姿态角度上的分布。鉴于单个冯米塞斯分布正在对分布形状做出强有力的假设，我们扩展了基本模型以预测von Mises分布的混合。我们展示了如何使用有限和无限数量的混合组件来学习混合模型。我们的模型允许在测试时进行基于可能性的训练和高效推理。我们在许多具有挑战性的姿态估计数据集上展示了我们的模型与当前最先进的技术相比产生校准的概率预测和竞争或优势点估计。

##### URL
[http://arxiv.org/abs/1805.03430](http://arxiv.org/abs/1805.03430)

##### PDF
[http://arxiv.org/pdf/1805.03430](http://arxiv.org/pdf/1805.03430)

