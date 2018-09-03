---
layout: post
title: "Multi-Cell Multi-Task Convolutional Neural Networks for Diabetic Retinopathy Grading Kang"
date: 2018-08-31 01:21:46
categories: arXiv_CV
tags: arXiv_CV CNN Classification Relation
author: Kang Zhou, Zaiwang Gu, Wen Liu, Weixin Luo, Jun Cheng, Shenghua Gao, Jiang Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Diabetic Retinopathy (DR) is a non-negligible eye disease among patients with Diabetes Mellitus, and automatic retinal image analysis algorithm for the DR screening is in high demand. Considering the resolution of retinal image is very high, where small pathological tissues can be detected only with large resolution image and large local receptive field are required to identify those late stage disease, but directly training a neural network with very deep architecture and high resolution image is both time computational expensive and difficult because of gradient vanishing/exploding problem, we propose a \textbf{Multi-Cell} architecture which gradually increases the depth of deep neural network and the resolution of input image, which both boosts the training time but also improves the classification accuracy. Further, considering the different stages of DR actually progress gradually, which means the labels of different stages are related. To considering the relationships of images with different stages, we propose a \textbf{Multi-Task} learning strategy which predicts the label with both classification and regression. Experimental results on the Kaggle dataset show that our method achieves a Kappa of 0.841 on test set which is the 4-th rank of all state-of-the-arts methods. Further, our Multi-Cell Multi-Task Convolutional Neural Networks (M$^2$CNN) solution is a general framework, which can be readily integrated with many other deep neural network architectures.

##### Abstract (translated by Google)
糖尿病视网膜病变（DR）是糖尿病患者中不可忽视的眼病，并且对DR筛查的自动视网膜图像分析算法的需求很高。考虑到视网膜图像的分辨率非常高，只能用大分辨率图像检测小病理组织，需要大的局部感受野来识别那些晚期疾病，而是直接训练具有非常深的结构和高分辨率图像的神经网络由于梯度消失/爆炸问题，时间计算昂贵且困难，我们提出了一种\ textbf {Multi-Cell}架构，它逐渐增加深度神经网络的深度和输入图像的分辨率，这既增加了训练时间，又增加了训练时间。提高分类准确性。此外，考虑到DR的不同阶段实际上逐渐进展，这意味着不同阶段的标签是相关的。为了考虑具有不同阶段的图像的关系，我们提出了一种\ textbf {Multi-Task}学习策略，该策略用分类和回归来预测标签。 Kaggle数据集的实验结果表明，我们的方法在测试集上达到了0.841的Kappa，这是所有现有技术方法的第4级。此外，我们的多小区多任务卷积神经网络（M $ ^ 2 $ CNN）解决方案是一个通用框架，可以很容易地与许多其他深度神经网络架构集成。

##### URL
[http://arxiv.org/abs/1808.10564](http://arxiv.org/abs/1808.10564)

##### PDF
[http://arxiv.org/pdf/1808.10564](http://arxiv.org/pdf/1808.10564)

