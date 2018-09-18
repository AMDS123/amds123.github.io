---
layout: post
title: "Revisit Multinomial Logistic Regression in Deep Learning: Data Dependent Model Initialization for Image Recognition"
date: 2018-09-17 11:23:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Transfer_Learning Classification Deep_Learning Detection Recognition
author: Bowen Cheng, Rong Xiao, Yandong Guo, Yuxiao Hu, Jianfeng Wang, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We study in this paper how to initialize the parameters of multinomial logistic regression (a fully connected layer followed with softmax and cross entropy loss), which is widely used in deep neural network (DNN) models for classification problems. As logistic regression is widely known not having a closed-form solution, it is usually randomly initialized, leading to several deficiencies especially in transfer learning where all the layers except for the last task-specific layer are initialized using a pre-trained model. The deficiencies include slow convergence speed, possibility of stuck in local minimum, and the risk of over-fitting. To address those deficiencies, we first study the properties of logistic regression and propose a closed-form approximate solution named regularized Gaussian classifier (RGC). Then we adopt this approximate solution to initialize the task-specific linear layer and demonstrate superior performance over random initialization in terms of both accuracy and convergence speed on various tasks and datasets. For example, for image classification, our approach can reduce the training time by 10 times and achieve 3.2% gain in accuracy for Flickr-style classification. For object detection, our approach can also be 10 times faster in training for the same accuracy, or 5% better in terms of mAP for VOC 2007 with slightly longer training.

##### Abstract (translated by Google)
我们在本文中研究如何初始化多项Logistic回归（完全连通层，其次是softmax和交叉熵损失）的参数，这被广泛用于深度神经网络（DNN）模型中的分类问题。由于广义已知逻辑回归不具有封闭形式的解决方案，因此通常随机初始化，导致若干缺陷，尤其是在转移学习中，其中除了最后任务特定层之外的所有层都使用预训练模型初始化。缺点包括收敛速度慢，陷入局部最小值的可能性以及过度拟合的风险。为了解决这些不足，我们首先研究逻辑回归的性质，并提出一种称为正则化高斯分类器（RGC）的闭合近似解。然后我们采用这种近似解决方案初始化任务特定的线性层，并在各种任务和数据集的准确性和收敛速度方面展示出优于随机初始化的性能。例如，对于图像分类，我们的方法可以将训练时间缩短10倍，并使Flickr样式分类的准确度增加3.2％。对于物体检测，我们的方法在相同精度的培训中也可以快10倍，对于VOC 2007的mAP而言，培训时间稍长一些也会提高5％。

##### URL
[http://arxiv.org/abs/1809.06131](http://arxiv.org/abs/1809.06131)

##### PDF
[http://arxiv.org/pdf/1809.06131](http://arxiv.org/pdf/1809.06131)

