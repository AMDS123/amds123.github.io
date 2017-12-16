---
layout: post
title: "Deep Neural Ensemble for Retinal Vessel Segmentation in Fundus Images towards Achieving Label-free Angiography"
date: 2016-09-19 19:11:05
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Classification
author: Avisek Lahiri, Abhijit Guha Roy, Debdoot Sheet, Prabir Kumar Biswas
mathjax: true
---

* content
{:toc}

##### Abstract
Automated segmentation of retinal blood vessels in label-free fundus images entails a pivotal role in computed aided diagnosis of ophthalmic pathologies, viz., diabetic retinopathy, hypertensive disorders and cardiovascular diseases. The challenge remains active in medical image analysis research due to varied distribution of blood vessels, which manifest variations in their dimensions of physical appearance against a noisy background. In this paper we formulate the segmentation challenge as a classification task. Specifically, we employ unsupervised hierarchical feature learning using ensemble of two level of sparsely trained denoised stacked autoencoder. First level training with bootstrap samples ensures decoupling and second level ensemble formed by different network architectures ensures architectural revision. We show that ensemble training of auto-encoders fosters diversity in learning dictionary of visual kernels for vessel segmentation. SoftMax classifier is used for fine tuning each member auto-encoder and multiple strategies are explored for 2-level fusion of ensemble members. On DRIVE dataset, we achieve maximum average accuracy of 95.33\% with an impressively low standard deviation of 0.003 and Kappa agreement coefficient of 0.708 . Comparison with other major algorithms substantiates the high efficacy of our model.

##### Abstract (translated by Google)
无标记眼底图像中视网膜血管的自动分割在计算辅助诊断眼病，即糖尿病性视网膜病，高血压病和心血管疾病方面起关键作用。由于血管分布的不同，在医学图像分析研究中仍然存在挑战，这种分布在嘈杂的背景下表现出其外观尺寸的变化。在本文中，我们将分割挑战作为分类任务来制定。具体而言，我们采用无监督的层次特征学习，使用两层稀疏训练去噪叠层自编码器的集合。利用bootstrap样本的一级培训可确保由不同网络架构形成的解耦和二级集成确保架构修订。我们表明，集合训练的自动编码器促进多样性学习词典的视觉内核船舶分割。 SoftMax分类器用于对每个成员自动编码器进行微调，并探索多种策略，以实现合奏成员的2级融合。在DRIVE数据集上，我们实现了95.33％的最高平均准确度，其标准偏差为0.003，Kappa协议系数为0.708。与其他主要算法的比较证实了我们模型的高效性。

##### URL
[https://arxiv.org/abs/1609.05871](https://arxiv.org/abs/1609.05871)

##### PDF
[https://arxiv.org/pdf/1609.05871](https://arxiv.org/pdf/1609.05871)

